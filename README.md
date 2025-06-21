# 🚀 AWS Bedrock RAG Chatbot (No Code Demo)

This repository contains documentation and resources for building a **Retrieval-Augmented Generation (RAG)** chatbot using **Amazon Bedrock**, **Lex**, and **S3**, without writing any custom code.

## 📁 Contents
- `docs/` – Contains sample travel policy documents used in the chatbot
- `README.md` – Setup instructions and explanation

## 🛠️ What It Does
This chatbot allows users to ask questions about travel policies using their own documents stored in S3. It uses:
- **Amazon Bedrock Knowledge Base** (with Titan Text Embeddings)
- **Amazon Lex** for the chatbot interface
- **Amazon S3** to store and retrieve documents

## 🧩 Technologies Used
- Amazon S3
- Amazon Bedrock
- Claude 3.5 Sonnet v2
- Titan Embeddings v2
- Amazon Lex

## 📚 How to Recreate It
1. Upload your policy documents to an S3 bucket
2. In Amazon Bedrock:
   - Create a knowledge base
   - Choose Titan Text Embeddings v2
   - Use Quick Create for vector store
3. Sync documents and test Q&A
4. Create a Lex bot and link it to the knowledge base

## 🗑️ Clean Up
- Delete the knowledge base, vector store, and S3 bucket to avoid charges

## 📌 Notes
- You must use an IAM user (not root)
- Set up a valid payment method in AWS
