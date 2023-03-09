OpenAI Explaination of  Physical Examination Report Chrome Extension
----------------------------------
最近刚做完体检，发现自己对于体检中的指标完全不清楚，于是想利用chatgpt做一个在线体检报告解读的想法；
这段代码fork [bob-plugin-openai-translator](https://github.com/yetone/bob-plugin-openai-translator) 



# 安装方法
1. 去 Release 页面下载 [openai-translator-chrome-extension-*.zip](https://github.com/yetone/openai-translator/releases) 文件
2. 解压缩下载后的 openai-translator-chrome-extension-*.zip 文件
3. 打开 Chrome 的 Extension 页面

<img width="600" src="https://user-images.githubusercontent.com/1206493/222926817-414b91ea-e90f-43f5-9fb3-e9b170b40ce8.png" />

4. 在 Extension 页面右上角打开 Developer mode，然后点击左上角的 Load unpacked 按钮，选择刚刚解压缩的目录即可安装完毕！（如果有旧版本记得先删除旧版本！）

<img width="600" src="https://user-images.githubusercontent.com/1206493/223045238-22c9b79b-205d-4f6b-a147-cc7cf4149c83.png" />

5. 去 [OpenAI](https://platform.openai.com/account/api-keys) 获取你的 API KEY

<img width="600" src="https://user-images.githubusercontent.com/1206493/223043946-0e7486ca-94d7-4324-a4f2-f62b9a3d527d.png" />

6. 把 API KEY 填入此插件配置界面的 API KEY 输入框中

<img width="600" src="https://user-images.githubusercontent.com/1206493/222958165-159719b4-28a5-44a4-b700-567786df7f03.png" />

7. 刷新浏览器页面，即可享受丝滑般的划词翻译体验 🎉
