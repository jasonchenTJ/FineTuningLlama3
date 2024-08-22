# FineTuningLlama3
Some scrips 4 FineTuningLlama3 by using unsloth


算力云服务器
https://www.autodl.com/home
费用：每小时 1.66元

机器配置：
CPU ：14 核心
内存：45 GB
GPU ：NVIDIA GeForce RTX 3090, 1

预训练大模型
Llama3-Chinese is a large model trained on 500k high-quality Chinese multi-turn SFT data, 100k English multi-turn SFT data, and 2k single-turn self-cognition data, using the training methods of DORA and LORA+ based on Meta-Llama-3-8B as the base.
https://www.modelscope.cn/models/seanzhang/Llama3-Chinese

模型微调框架
unsloth
https://unsloth.ai/
Finetune Llama 3.1, Mistral, Phi-3 & Gemma 2-5x faster with 80% less memory!
更少的内存，更好的性能

数据集采样
客户化定制数据集采样：来自于麦库笔记
json 文件格式用例：

[
{
 "output": "Jason,Keep going!" 
}]


