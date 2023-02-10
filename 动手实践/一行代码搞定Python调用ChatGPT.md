# 一行Python代码搞定ChatGPT调用
## API key获取
打开openapi官网：
[https://platform.openai.com/account/api-keys](https://platform.openai.com/account/api-keys)

登录后点击账户这里的查看API key：

![查看账户API key](https://github.com/summerjava/awesome-chatgpt/blob/main/%E5%8A%A8%E6%89%8B%E5%AE%9E%E8%B7%B5/%E4%B8%80%E8%A1%8C%E4%BB%A3%E7%A0%81%E6%90%9E%E5%AE%9APython%E8%B0%83%E7%94%A8ChatGPT1.png)

然后创建属于自己的API key，记得保存下来，不要公开。

![创建API key](https://github.com/summerjava/awesome-chatgpt/blob/main/%E5%8A%A8%E6%89%8B%E5%AE%9E%E8%B7%B5/%E4%B8%80%E8%A1%8C%E4%BB%A3%E7%A0%81%E6%90%9E%E5%AE%9APython%E8%B0%83%E7%94%A8ChatGPT2.png)

## POAI库安装
然后安装poai库：

	pip install poai


## 一行Python代码
python代码很简单，完整的如下：

	import poai
	poai.chatgpt.chat(api_key='自己的API key', prompt='计算机大学排名？')
	
	
运行结果如下：
![运行结果](https://github.com/summerjava/awesome-chatgpt/blob/main/%E5%8A%A8%E6%89%8B%E5%AE%9E%E8%B7%B5/%E4%B8%80%E8%A1%8C%E4%BB%A3%E7%A0%81%E6%90%9E%E5%AE%9APython%E8%B0%83%E7%94%A8ChatGPT3.png)
