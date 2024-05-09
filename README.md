# Efficiently_Serving_LLMs
[Complete](https://learn.deeplearning.ai/accomplishments/9c630593-7922-464a-9af7-535125deed06?usp=sharing)
LLM Serving refers to the process of deploying and running large language models (LLMs) to handle user requests. It involves taking an LLM, which is typically trained offline, and setting it up to respond to queries in real-time.
![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSKz9pXYJ2UJfYZomKgxUVg2r38QqSJ9_IDag&usqp=CAU)

![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSN1II7V4Ra3l7N86_tZyWRAbfcxegt5mS52A&usqp=CAU)
Predibase is focused on individuals and organizations who have tried operationalizing machine learning, but found themselves re-inventing the wheel each step of the way. Our declarative approach allows users to focus on the “what” of their ML tasks while leaving our system to figure out the “how”. In this post, we’ll share more about our journey, the value we bring to both large Fortune 500 enterprises and high-growth startups, and what’s coming up next.

Predibase offers state-of-the-art fine-tuning techniques out of the box such as quantization, low-rank adaptation, and memory-efficient distributed training to ensure your fine-tuning jobs are fast and efficient—even on commodity GPUs.

![](https://github.com/ksm26/Efficiently-Serving-LLMs/blob/main/images/1_1.png)

**Auto-Regressive Models:** Understand how auto-regressive large language models generate text token by token.
![](https://github.com/ksm26/Efficiently-Serving-LLMs/blob/main/images/1_2.png)
![](https://github.com/ksm26/Efficiently-Serving-LLMs/blob/main/images/1_3.png)
![](https://github.com/ksm26/Efficiently-Serving-LLMs/blob/main/images/1_4.png)

**LLM Inference Stack:** Implement foundational elements of a modern LLM inference stack, including KV caching, continuous batching, and model quantization.
![](https://github.com/ksm26/Efficiently-Serving-LLMs/blob/main/images/2_1.png)
![](https://github.com/ksm26/Efficiently-Serving-LLMs/blob/main/images/2_2.png)
![](https://github.com/ksm26/Efficiently-Serving-LLMs/blob/main/images/3_3.png)

**LoRA Adapters:** Explore the details of how Low Rank Adapters (LoRA) work and how batching techniques allow different LoRA adapters to be served to multiple customers simultaneously.
![](https://github.com/ksm26/Efficiently-Serving-LLMs/blob/main/images/5_1.png)
![](https://github.com/ksm26/Efficiently-Serving-LLMs/blob/main/images/5_2.png)
**Hands-On Experience:** Get hands-on with Predibase’s LoRAX framework inference server to see optimization techniques in action.

**Key Points**
- 🔎 Learn techniques like KV caching to speed up text generation in Large Language Models (LLMs).
- 💻 Write code to efficiently serve LLM applications to a large number of users while considering performance trade-offs.
- 🛠️ Explore the fundamentals of Low Rank Adapters (LoRA) and how Predibase implements them in the LoRAX framework inference server.
