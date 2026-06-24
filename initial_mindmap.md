# AI & ML Roadmap — From Scratch to AI Agents

This document is designed to build a complete mental model of AI from the ground up.

The goal is not to learn coding first.

The goal is to understand:

- What AI is
- What ML is
- What DL is
- What Models are
- How Models are created
- What Transformers are
- What LLMs are
- What RAG is
- What AI Agents are
- How modern AI products are built

---

# Table of Contents

1. What is Artificial Intelligence (AI)?
2. What is Machine Learning (ML)?
3. What is a Model?
4. How Models Are Created
5. Traditional Machine Learning Algorithms
6. What is Deep Learning (DL)?
7. What is a Neural Network?
8. Deep Learning Architectures
9. What is NLP?
10. What is Computer Vision?
11. What is a Transformer?
12. What is an LLM?
13. What is Generative AI?
14. What are Embeddings?
15. What is a Vector Database?
16. What is RAG?
17. What is an AI Agent?
18. What is Orchestration?
19. Complete AI Hierarchy
20. Learning Order

---

# 1. What is Artificial Intelligence (AI)?

## Definition

Artificial Intelligence is the field of building systems that can perform tasks that normally require human intelligence.

Examples:

- Understanding language
- Recognizing images
- Making decisions
- Solving problems
- Learning from data

---

## Real Life Examples

### ChatGPT

```text
Question
↓
Answer
```

### Google Maps

```text
Traffic Data
↓
Best Route
```

### Self Driving Car

```text
Camera
↓
Understand Road
↓
Drive
```

---

## AI Hierarchy

```text
Artificial Intelligence
│
├── Rule Based AI
├── Machine Learning
├── Computer Vision
├── NLP
└── Robotics
```

---

# 2. What is Machine Learning (ML)?

## Definition

Machine Learning is a branch of AI where systems learn patterns from data instead of being explicitly programmed.

Traditional Programming:

```text
Rules
+
Data
↓
Answer
```

Machine Learning:

```text
Data
+
Answers
↓
Model Learns Rules
```

---

## Real Life Examples

### Netflix

```text
Watch History
↓
Recommendations
```

### Amazon

```text
Purchase History
↓
Product Suggestions
```

### Fraud Detection

```text
Transactions
↓
Fraud or Not
```

---

# 3. What is a Model?

## Definition

A Model is the final learned system produced after training.

Think of it as:

```text
Knowledge
Stored
Inside
A Mathematical Structure
```

---

## Example

Training:

```text
House Data
↓
Learning
↓
House Price Model
```

Usage:

```text
New House
↓
Model
↓
Predicted Price
```

---

## Real Life Analogy

```text
Student Studies
↓
Knowledge Learned
↓
Student Takes Exam
```

The student is equivalent to the trained model.

---

# 4. How Models Are Created

Every model follows:

```text
Data
↓
Algorithm / Architecture
↓
Training
↓
Model
```

---

## Example 1

```text
House Prices
+
Linear Regression
↓
House Price Model
```

---

## Example 2

```text
Internet Text
+
Transformer
↓
GPT
```

---

# 5. Traditional Machine Learning Algorithms

These are algorithms used to create models.

---

## Linear Regression

### Purpose

Predict a number.

### Example

```text
House Features
↓
House Price
```

---

## Logistic Regression

### Purpose

Classification.

### Example

```text
Email
↓
Spam / Not Spam
```

---

## Decision Tree

### Purpose

Decision making through conditions.

### Example

```text
Income?
↓
Age?
↓
Loan Approved?
```

---

## Random Forest

### Purpose

Many decision trees combined.

### Example

```text
Fraud Detection
```

---

## KNN

### Purpose

Find similar examples.

### Example

```text
Recommend Similar Products
```

---

## SVM

### Purpose

Separate categories.

### Example

```text
Cat vs Dog
```

---

## Naive Bayes

### Purpose

Probability based classification.

### Example

```text
Spam Detection
```

---

## XGBoost

### Purpose

Powerful tabular data prediction.

### Example

```text
Customer Churn Prediction
```

---

# 6. What is Deep Learning (DL)?

## Definition

Deep Learning is a branch of Machine Learning based on Neural Networks.

```text
AI
└── ML
     └── DL
```

---

## Why Deep Learning?

Traditional ML struggles with:

- Images
- Audio
- Video
- Human Language

Deep Learning excels at these.

---

## Real Life Examples

### Face Recognition

```text
Photo
↓
Person Identified
```

### ChatGPT

```text
Question
↓
Answer
```

### Midjourney

```text
Prompt
↓
Image
```

---

# 7. What is a Neural Network?

## Definition

A Neural Network is a mathematical structure inspired by the human brain.

---

## Structure

```text
Input Layer
↓
Hidden Layers
↓
Output Layer
```

---

## Example

```text
Picture
↓
Neural Network
↓
Cat
```

---

## Important

```text
Deep Learning
↓
Neural Networks
```

Every major modern AI model uses neural networks.

---

# 8. Deep Learning Architectures

## CNN

### Full Form

Convolutional Neural Network

### Best For

Images

### Examples

```text
Face Detection
Image Classification
Medical Imaging
```

---

## RNN

### Best For

Sequential Data

### Examples

```text
Text
Speech
Time Series
```

---

## LSTM

Improved version of RNN.

Used for remembering longer context.

---

## Transformer

Most important architecture today.

Used in:

```text
GPT
Claude
Gemini
Llama
DeepSeek
```

---

## GAN

Generative Adversarial Network

Used for:

```text
Image Generation
```

---

## Diffusion Models

Used by:

```text
Midjourney
DALL-E
Stable Diffusion
```

---

# 9. What is NLP?

## Full Form

Natural Language Processing

---

## Definition

Field of AI focused on understanding human language.

---

## Examples

### Translation

```text
English
↓
Hindi
```

### Summarization

```text
Long Article
↓
Short Summary
```

### Sentiment Analysis

```text
Review
↓
Positive / Negative
```

---

# 10. What is Computer Vision?

## Definition

Field of AI focused on images and videos.

---

## Examples

### Face Recognition

```text
Image
↓
Person
```

### OCR

```text
Image
↓
Text
```

### Object Detection

```text
Image
↓
Car
Person
Dog
```

---

# 11. What is a Transformer?

## Definition

A Transformer is a Deep Learning architecture specialized for understanding relationships between words and tokens.

---

## Importance

The Transformer revolutionized NLP.

Paper:

```text
Attention Is All You Need
(2017)
```

---

## Used By

```text
GPT
Claude
Gemini
Llama
DeepSeek
```

---

# 12. What is an LLM?

## Full Form

Large Language Model

---

## Definition

A Transformer trained on huge amounts of text.

---

## Formula

```text
Transformer
+
Massive Data
+
Training
↓
LLM
```

---

## Examples

```text
GPT
Claude
Gemini
Llama
Qwen
DeepSeek
```

---

# 13. What is Generative AI?

## Definition

AI that creates new content.

---

## Examples

### Text

```text
GPT
Claude
Gemini
```

### Images

```text
Midjourney
DALL-E
Stable Diffusion
```

### Video

```text
Sora
Veo
```

---

## Relationship

```text
AI
└── ML
     └── DL
          └── Generative AI
```

---

# 14. What are Embeddings?

## Definition

Embeddings convert text into numerical vectors.

---

Example:

```text
"Dog"
↓
[0.12, 0.45, 0.89 ...]
```

---

## Why?

Computers understand numbers, not words.

---

## Used In

- Search
- RAG
- Recommendations
- Semantic Similarity

---

# 15. What is a Vector Database?

## Definition

Database optimized for storing embeddings.

---

## Examples

```text
Chroma
Qdrant
Pinecone
Weaviate
pgvector
```

---

## Purpose

```text
Question
↓
Find Similar Content
↓
Return Results
```

---

# 16. What is RAG?

## Full Form

Retrieval Augmented Generation

---

## Definition

A system that retrieves relevant information before asking the LLM to answer.

---

## Flow

```text
Documents
↓
Chunking
↓
Embeddings
↓
Vector DB
↓
Retriever
↓
LLM
↓
Answer
```

---

## Real Life Examples

- PDF Chatbot
- Company Knowledge Base
- University Assistant
- Legal Assistant

---

# 17. What is an AI Agent?

## Definition

An AI system capable of taking actions.

---

## Structure

```text
AI Agent
│
├── Model
├── Memory
├── Tools
├── APIs
├── Planning
└── Actions
```

---

## Example

Travel Agent

```text
User
↓
Find Flight
↓
Flight API
↓
Book Flight
```

---

## Important

```text
Model ≠ Agent
```

Agent uses a model.

---

# 18. What is Orchestration?

## Definition

Coordinating multiple AI components together.

---

## Flow

```text
User
↓
Agent
↓
LLM
↓
Vector DB
↓
Search
↓
API
↓
Database
```

---

## Frameworks

```text
LangGraph
CrewAI
AutoGen
MCP
```

---

# 19. Complete AI Hierarchy

```text
ARTIFICIAL INTELLIGENCE (AI) 
│ 
├── Rule-Based AI 
│    ├── Expert Systems 
│    ├── Decision Rules 
│    └── Logic Systems 
│ 
├── Machine Learning (ML) 
|    │ 
│    ├── Traditional ML 
│    │    │ 
│    │    ├── Algorithms 
│    │    │    ├── Linear Regression 
│    │    │    ├── Logistic Regression 
│    │    │    ├── Decision Tree 
│    │    │    ├── Random Forest 
│    │    │    ├── KNN 
│    │    │    ├── SVM 
│    │    │    ├── Naive Bayes 
│    │    │    ├── XGBoost 
│    │    │    ├── LightGBM 
│    │    │    └── CatBoost 
│    │    │ 
│    │    └── Trained Models 
│    │         ├── House Price Predictor 
│    │         ├── Fraud Detector  
│    │         ├── Churn Predictor 
│    │         └── Sales Forecaster 
│    │ 
│    └── Deep Learning (DL) 
│         │    
│         ├── Neural Networks 
│         │
│         ├── Feed Forward Networks 
│         │ 
│         ├── CNN 
│         │    ├── Image Classification 
│         │    ├── Face Detection 
│         │    └── Object Detection 
│         │ 
│         ├── RNN 
│         │    
│         ├── LSTM 
│         │ 
│         ├── Transformer 
│         │    |
│         │    ├── GPT 
│         │    ├── Claude 
│         │    ├── Gemini 
│         │    ├── Llama 
│         │    ├── DeepSeek 
│         │    ├── Qwen 
│         │    └── Mistral 
│         │ 
│         ├── GAN 
│         │ 
│         └── Diffusion Models 
│              ├── Midjourney 
│              ├── Stable Diffusion 
│              └── DALL-E 
│         
├── Computer Vision 
│ ├── Image Classification 
│ ├── Object Detection 
│ ├── OCR 
│ └── Segmentation
| 
│ ├── NLP 
│ ├── Sentiment Analysis 
│ ├── Translation 
│ ├── Summarization 
│ └── Question Answering 
│ 
└── Robotics
```

---

# 20. Learning Order

Learn in this exact order:

```text
1. AI
↓
2. Machine Learning
↓
3. Models
↓
4. Traditional ML Algorithms
↓
5. Deep Learning
↓
6. Neural Networks
↓
7. NLP
↓
8. Computer Vision
↓
9. Transformers
↓
10. LLMs
↓
11. Generative AI
↓
12. Embeddings
↓
13. Vector Databases
↓
14. RAG
↓
15. AI Agents
↓
16. Orchestration
```

---

# Core Mental Model

```text
Data
+
Algorithm / Architecture
↓
Training
↓
Model
↓
Model + Tools + Memory
↓
AI Agent
↓
Multiple Agents + Systems
↓
Orchestration
```

If you understand the above hierarchy, you can accurately place almost every modern AI technology—from Linear Regression to GPT, from RAG chatbots to autonomous AI agents.