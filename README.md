# llm-workshop-quick-start 实验手册

## 1 部署 Falcon-7B模型

本实验我们将使用 HuggingFace TGI 容器将 Falcon-7B模型部署到 SageMaker Endpoint 上并调用。

Notebook 对应 [部署 Falcon-7B模型.ipynb](./部署%20Falcon-7B模型.ipynb)

## 2 部署自有（Finetune后）模型

本实验我们将使用 AWS Large Model Inference （LMI）部署自己 finetune 的模型到 SageMaker Endpoint 上并调用。Finetune 模型我们可以跳过，并从 HF Hub下载一个模型并上传到 S3，以此模拟 Finetune 后模型的状态。

Notebook 对应 [Deploy-llama-on-SageMaker](./Deploy-llama-on-SageMaker.ipynb)

## 3 Finetune Alpaca （参考）

GitHub repo： https://github.com/snowolf/alpaca-on-amazon-sagemaker
