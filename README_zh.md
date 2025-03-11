# 🌍✨ **智能旅游助手** ✨🌍

[ [English](https://claude.ai/chat/README.md) | 中文 ]

欢迎使用**智能旅游助手**——探索**中国江西省吉安市**的交互式指南！🏯🌿

我们的系统采用前沿人工智能技术构建，整合了**大型语言模型(LLMs)** 🤖、**检索增强生成(RAG)** 📚和**LangChain** 🔗，确保您获得**准确、有见地且与上下文相关**的旅游和文化信息。🎒📍

![nothing](./pictures/UI.png)

## 🎥 **演示视频**

您可以在项目目录中找到演示视频： 📂 `./pictures/demo_video.mp4` 🎬🎶

## 🛠️ **环境设置**

按照以下步骤顺利设置您的环境：🚀

```powershell
pip install -r requirements.txt
conda install -q ffmpeg  # 确保ffmpeg==4.2.2
```

由于LLM模型需要**大内存**，因此**无法**上传到GitHub。❌💾 请在运行应用程序前准备好您自己的模型（包括**LLM**和**GAN**）。

在我们的项目中，主要使用： 

✅ **Baichuan2** 🧠 用于生成回复 

✅ **Wav2Lip** 🗣️🎥 用于制作数字人视频

## 🚀 **运行应用程序**

我们使用**Vue 3** 🖥️构建直观的UI，并使用**FastAPI** ⚡为数字人视频提供后端支持。

要启动应用程序，只需运行：

```powershell
python main.py
```

✨ **一切就绪，开始体验吧！** 🎉

## 📊 **我们的数据集**

我们收集了关于吉安市**旅游和文化亮点**的**丰富数据集** 🏕️🛶，这些数据来自各种平台。您可以在**`our_data`**目录中探索详细信息。

要上传新数据，请使用我们方便的Python脚本：🐍📤

```powershell
python ./upload_data_to_upload.py
```

📌 **注意：**如果遇到任何问题，请查阅[Pinecone文档](https://docs.pinecone.io/guides/data/upsert-data)中的最新指南。📖🔗

## 🖥️ **我们的网页界面**

我们使用**Vue 3** 🏗️构建了**交互式网页界面**，以确保流畅且动态的用户体验。

要设置和运行前端，请安装必要的依赖项（需要**Node.js**）并运行：

```powershell
npm install
npm run dev
```

🎨 **享受流畅的UI体验！** 🎭✨

🌐 **也可以直接在以下网址探索UI：** https://ff-ovo.fun/ 🚀🔗

## 📚 **参考资料**

📖 **[数字人智能对话系统 - Linly-Talker: "与您的虚拟自我进行交互式对话"](https://github.com/Kedreamix/Linly-Talker)**

## 💖 **致谢**

🚀 **共同创作者:** [WiserZhou](https://github.com/WiserZhou) 与 [yiranbue](https://github.com/yiranbue)

🌟 感谢查看我们的项目！**我们希望这个项目能够提供一些帮助！** ✈️🏯✨