# 🎓 UniFliXsg: AI-Powered Undergraduate Program Recommendations for Singapore Universities

Welcome to UniFliXsg! This AI-powered app helps you find the perfect undergraduate program in Singapore based on your interests and career goals. Currently, UniFliXsg covers single major programs at NUS, NTU, SMU, and SUTD.

Try it out here: UniFliXsg on [Hugging Face](https://huggingface.co/spaces/oadultradeepfield/uniflixsg?source=post_page-----b9b448f7ea19--------------------------------) 🚀

## 🛠️ Project Overview
UniFliXsg leverages AI to recommend university programs by matching your profile with program details. We use a content-based filtering approach, similar to semantic search, to suggest programs that align with your interests and career aspirations.

## 🔍 How it Works:

- **User Input**: You provide your interests and career goals.
- **Text Embedding**: We use lightweight models from Hugging Face's sentence transformers to convert the user profile and program details into vectors.
- **Cosine Similarity**: The similarity between your profile and each program is calculated, and the top recommendations are displayed.

For a detailed breakdown of the workflow and technical aspects, check out the full article on [Medium](https://oadultradeepfield.medium.com/uniflixsg-ai-powered-undergraduate-program-recommendations-for-singapore-universities-b9b448f7ea19) 📝.

## 🔧 Tech Stack
- **Gradio**: For building and deploying the app's interface.
- **Hugging Face Transformers**: For text embedding and model management.
- **Python** is the core programming language used for the entire project.

## 💾 Data Collection
The dataset was manually compiled from official university websites and is stored in a parquet file format. The data preprocessing was done using Polars for its speed over Pandas.

## 🚀 Deployment
The app is live and can be accessed via the Hugging Face Space. Built with Gradio, it is user-friendly and doesn't require extensive web development knowledge to modify.

## 🙌 Acknowledgments
A big thank you to the community and everyone who supported this project! Your feedback on LinkedIn and other platforms was invaluable. Special shoutout to Gradio for their engagement!

For more insights and updates on my projects, follow me on [Medium](https://oadultradeepfield.medium.com/) and [LinkedIn](https://www.linkedin.com/in/psrisukhawasu/).
