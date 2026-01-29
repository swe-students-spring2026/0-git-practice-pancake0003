# Interesting Article
[AMD MI300x GPUs with GEMM tuning improves throughput and latency by up to 7.2x](https://news.ycombinator.com/item?id=40828394)
## My Thoughts
I came across this article during my internship trying to gemm tune some LLMs, and found the heated arguments under this thread to be immensely entertaining. Although the topic here doesn't directly relate to software engineering, I do think that it takes many skilled engineers to come up with solutions to these problems, and the fact that people would debate on whether AMD or NVIDIA GPUs are better just proves that the competition is cutting very close. Reading the thread, it's also obvious that many hold strong beliefs for a certain model/GPU/method, which is funny because every time someone expresses their disagreement to the previous thread, someone else replies with another disagreement. 

## Comment from Laiyi
I like how you connect the thread to real engineering work from your internship. Even if it is not a classic software engineering article, performance tuning for GEMM and LLM workloads is a great example of engineering tradeoffs in practice. The debate itself is also a useful signal, because it shows how sensitive results are to assumptions like kernel choices, memory bandwidth limits, compiler stacks, and benchmarking setup.
