# 🚀 LLM Fine-Tuning for Text Summarization

This project fine-tunes the **T5 model** (Text-to-Text Transformer) for **text summarization**, using a subset of the **CNN/DailyMail** news dataset. The T5 model excels at converting text into meaningful summaries, making it a great choice for sequence-to-sequence tasks.

🔗 **[Dataset link](https://www.kaggle.com/datasets/gowrishankarp/newspaper-text-summarization-cnn-dailymail)**

## Why T5-Small?

Due to computational constraints, I opted for the **T5-small** variant over larger models like T5-base or T5-large. Here's why:

- **T5-Small (60M params)**: Lightweight, fast, and suitable for limited resources.
- **T5-Base (220M params)**: Balanced but requires more resources.
- **T5-Large (770M params)**: Most powerful, but memory-intensive.

Using a **T4 GPU**, I trained T5-small efficiently while meeting resource limits.

## Key Features 📝

- **512 token inputs**, summarized to **150 token outputs**.
- Pre-processed dataset for optimal text length.
- Limited to a **5,000 record** sample for training (you can expand this!).
  
While no hyperparameter tuning was applied due to limitations, you can **experiment** with learning rates, batch size, and epochs to further improve the model's performance.

## Get Started 🌟

This project is a **starting point** for anyone interested in fine-tuning T5 for summarization. Feel free to:

- **Clone the repo** and adapt the dataset or model configurations.
- **Experiment with hyperparameters** to boost performance.
- **Expand the dataset** for larger-scale training.

## Why It Matters 🚀

Fine-tuning pre-trained models like T5 is a game-changer for businesses, allowing efficient adaptation for niche tasks without the need for training from scratch. It saves time, resources, and improves performance in specific applications.

## Next Steps

Ready to dive in? Check out the code, run it on your own data, and tweak the settings to see how well T5 performs!

---

Developed by **Gonçalo Casanova Brito**.  
🔗 Connect on [LinkedIn](https://linkedin.com/in/goncalobrito)  
🔗 Check my work on [GitHub](https://github.com/goncasbrito) or [Kaggle](https://kaggle.com/goncasbrito98)
