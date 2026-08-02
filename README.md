# LLM Systems Lab

一个无需后端的中文大模型推理交互学习网站。

## 在线访问

https://pangpangDaddy.github.io/llm-systems-lab/

## 课程内容

- 一次 Token 的生成过程
- Embedding、Q/K/V、Attention、Transformer、Logits 与采样
- Prefill 与 Decode 的区别
- KV Cache 的写入时序与注意力读取
- KV Cache 分页、连续批处理、Prefix 共享、Admission Control
- GPU / CPU / SSD 分层缓存与 LRU 淘汰模拟
- 1M 上下文：RoPE 扩展、长序列训练、Chunked Prefill、Context Parallel
- Dense / Sliding Window / Hybrid Sparse Attention 交互对比
- 1M KV 容量、P→D 传输与多 GPU 分片估算
- 支持 1K～1M 上下文的 8GB 显存估算器

## 本地运行

直接用浏览器打开 `index.html`，无需安装依赖或启动服务器。

## 说明

动画中的 Token ID、向量、概率及调度数据为教学示意；机制和数据流按 Decoder-only Transformer 及常见推理服务架构设计。
