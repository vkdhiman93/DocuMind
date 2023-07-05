# DocuMind


Introducing [DocuMind] – the innovative app designed to revolutionize the way you interact with your files. This app showcases the power of LLMs to create a unique file management experience. With DocuMind, you can effortlessly index and search through your PDFs, text files, and multimedia files, empowering you to have meaningful interactions with them.


The main factor that motivated us for developing DocuMind is the diversity of data we have to deal with on a daily basis. Frequently, we encounter a common challenge that involves the need to reference specific sections of files such as research papers, manuals, or recorded meetings. However, the traditional manual search process can be time-consuming, exhausting, and often fails to provide quick and accurate results. So, we thought how can we combine the interactions with all these different forms of data on a single platform? And that’s how DocuMind was born.
 
 
So how does DocuMind work? Quite simple. The backbone of DocuMind are these components:
1. PyPDF to convert PDF files into simple text.
2. OpenAI Whisper for transcribing your audio and video files into text.
3. Langchain for indexing the textual information.
4. Sentence Transformer ‘all-mpnet-base-v2’ embeddings for filtering information.
5. Databricks Dolly LLM for language processing
6. Streamlit for the straightforward UI
 
 
DocuMind takes file management to the next level by transforming your documents into interactive knowledge hubs. Simply ask a question, and the app's intelligent algorithms will swiftly filter through your file, pinpointing the exact answers you need. No need to dig endlessly through your files – DocuMind brings the information you seek right away.


But that's not all! DocuMind goes beyond just providing answers. It also showcases the source of information, allowing you to trace back in case you want to get a bit deeper. Whether you're a researcher, a student, a professional, or simply someone with a vast digital library, DocuMind enables you to have meaningful conversations with your files, unlocking their full potential and transforming the way you interact with your knowledge.


The main challenge we faced was how we can set up an architecture for deployment of DocuMind. Thanks to the seamless integration of Databricks and AWS cluster, we achieved a quick deployment of the app, saving significant time and effort in setup and management. Leveraging the GPU capabilities of AWS helped us further enhance the app's performance. To provide an intuitive user experience, we chose Streamlit as the framework to power DocuMind, ensuring a simple and intuitive interface. This combination of technologies and platforms enabled us to deliver an efficient and enjoyable user experience with ease.
 
 
DocuMind is an exciting demonstration of what's possible when cutting-edge open-source technologies are combined. Even with such smaller LLMs, we were able to implement a quite effective platform for improving the user experience in file management. This made us understand what we could accomplish with more time and democratization of AI, will in turn empower the users and programmers. It showcases the potential to streamline file management, enhance productivity, and unlock the full potential of your files.


It’s just a starting point for us. We further plan to include handling capabilities for more different types of files and expand it into a larger platform where you could integrate visual data, code-based text and more. So, take a leap and experience the future of file management with DocuMind. For us, it’s only matter of time even the operating systems would come integrated with AI-assisted techniques. And our effort is nothing but a small step in that direction.
