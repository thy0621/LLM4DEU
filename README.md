# LLM4DEU
Fine Tuning Large Language Model for Medical Diagnosis in Outpatient and Emergency Department Visits of Neurosurgery
神外医学诊断大模型项目（LLM4DEU）拟通过大模型方式实现神经外科领域疾病诊断及知识问答等任务，推动神外领域知识问答、临床辅助诊疗等领域的快速发展。

目前针对神经外科领域的疾病诊断任务，发布了神外疾病诊断指令微调大模型LLM4DEU。



## 更新日志
[2024/05/12] 面向神经外科领域的疾病诊断的大模型LLM4DEU

[2023/09] 项目启动

## A Quick Start
1. 首先需要下载ChatGLM-6B原始模型代码和参数，并配置依赖环境（ChatGLM-6B: https://github.com/THUDM/ChatGLM-6B ）。
2. 下载 LLM4DEU 模型参数，将checkpoint压缩文件解压到 ChatGLM-6B/ptuning/ 路径下

百度网盘链接: 链接: https://pan.baidu.com/s/1-gExh9vBJgMu_sgOVeYtzw 提取码: nbc2 

[## 项目参与者
本项目由北京科技大学王睿、王博然团队和北京交通大学计算机与信息技术学院医学智能团队田昊宇、刘一铭、戴芯瑜等完成，项目负责人周雪忠老师。另外，感谢天坛医院等多家合作单位提供的医疗数据。]: #

## 致谢
本项目参考了以下开源项目，在此对相关项目和研究开发人员表示感谢。
- ChatGLM-6B: https://github.com/THUDM/ChatGLM-6B
- Facebook LLaMA: https://github.com/facebookresearch/llama
- Stanford Alpaca: https://github.com/tatsu-lab/stanford_alpaca
- Huatuo: https://github.com/SCIR-HI/Huatuo-Llama-Med-Chinese

  
## 免责声明

本项目相关资源仅供学术研究之用，严禁用于商业用途。使用涉及第三方代码的部分时，请严格遵循相应的开源协议。模型生成的内容受模型计算、随机性和量化精度损失等因素影响，本项目无法对其准确性作出保证。本项目数据集绝大部分由模型生成，即使符合某些医学事实，也不能被用作实际医学诊断的依据。对于模型输出的任何内容，本项目不承担任何法律责任，亦不对因使用相关资源和输出结果而可能产生的任何损失承担责任。


## Citation

如果你使用了本项目的数据或者代码，请声明引用

	  @misc{alpaca,
	  author={W, T, L, D},
	  title = {LLM4DEU},
	  year = {2023},
	  publisher = {GitHub},
	  journal = {GitHub repository},
	  howpublished = {\url{https://github.com/thy0621/LLM4DEU}},
	}


