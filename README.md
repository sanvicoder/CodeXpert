# CodeXpert: Real-Time Code Error Detection System

**Tech Stack:** Java • Python • Spring Boot • FastAPI • REST APIs • Google Colab • DeepSeek Coder (LLM)

##  Overview
**CodeXpert** is a full-stack intelligent code error detection system designed to assist developers in identifying **syntax** and **logical errors** in Java, Python, and C++ code in real-time. The system leverages a modular **microservices architecture** that combines the robustness of **Spring Boot** for backend routing and UI communication with the flexibility of **FastAPI** and the intelligence of **DeepSeek Coder** large language model (LLM) hosted on **Google Colab**.

---

##  Key Features

-  **Real-time error detection** for Java, Python, and C++ code.
-  **Modular architecture** using Spring Boot and FastAPI microservices.
-  Integration with **DeepSeek Coder Instruct** LLM for logical code understanding and suggestions.
-  **RESTful APIs** for seamless communication between services.
-  Hosted LLM inference via **Google Colab** for rapid prototyping and scalability.

---

##  System Architecture

```text
[ Frontend (Optional) ] --> [ Spring Boot Backend (Router + API Gateway) ] --> [ FastAPI Microservice ] --> [ DeepSeek Coder (Google Colab) ]
