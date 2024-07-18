# 📬 LlaMail
A Windows console email client powered by LlamaCpp

## 📰 Project Background
The idea of having to read endless amounts of email is cumbersome, many may agree that their inbox is a sheer mess. To address this dilemma, we make use of generative ai to formulate a response to an email read using imap. This debatebly eliminates skipping or missing an email and can help drive the cause towards inbox zero. Furthermore, it is strongly inspired by the Semantic Kernel's Function Calling [Stepwise](https://github.com/microsoft/semantic-kernel/blob/main/python/samples/getting_started/05-using-the-planner.ipynb) Planner by [Microsoft](https://www.microsoft.com)

## 🗺️ Getting started
- Firstly, you'll need to have the (1) mail server address for your email server, (2) the email address of the account you would like to log into and (3) the password. Imap uses port 587 for sending emails, which is hardcoded as default.
- Ensure that you have [LlamaCpp](https://github.com/ggerganov/llama.cpp) installed
- Clone the [APIinaShell](https://github.com/perpendicularai/APIinaShell) repo and serve it with your GGUF model of choice. You may obtain a copy of a gguf model from [Huggingface](https://huggingface.co/models?sort=trending&search=gguf).
- Serve the model with your desired host and port configuration.
- Once that has been done, navigate to [releases](https://github.com/perpendicularai/LlaMail/releases), then first download the zip archive named source code, extract the contents and then download the msixbundle and store it in the same directory. From here you have either the option of installing it using Powershell or by double-clicking the msixbundle package. Once the program has been installed, can it then be launched from the start-menu. See below:
![test_1](https://github.com/perpendicularai/OllaMail/assets/146530480/0e62d37e-2859-4118-a10a-3c3ade7fdbd5)

![test_0](https://github.com/user-attachments/assets/ab0e5dbd-6d40-4d63-8dcd-57d535165077)

