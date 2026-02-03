Here’s a **clean, exam-/interview-ready cheat sheet for MCP (Model Context Protocol)** distilled from your uploaded *Introduction to MCP* material 

---

# 🧠 Model Context Protocol (MCP) — Cheat Sheet

## What is MCP?

**MCP (Model Context Protocol)** is an **open, standardized protocol** that defines **how AI applications connect to external tools and data**.

> In short: **MCP = the bridge between LLMs and the real world** 🌍

---

## Why MCP Exists

LLMs alone only know:

* Their **training data**
* What’s in the **current prompt**

But real apps need access to:

* 📅 Calendars
* 🗂️ File systems
* 🗄️ Databases
* 📧 Emails
* 🔧 External tools & APIs

👉 MCP provides a **standard way** to pass this context and capability to AI models 

---

## MCP in One Line

> **An open-source standard protocol for connecting AI applications to external tools and data** 

---

## Key Terms Breakdown

### 1. **Standard**

* A **shared agreement** on how things should work
* Ensures **compatibility** across systems
* Not a product → a **common contract**

### 2. **Protocol**

* A set of **communication rules**
* Defines:

  * Message format
  * Message order
  * Message meaning

### 3. **Open**

* Publicly available
* Anyone can implement it
* Created by **Anthropic**, but **not proprietary** 

---

## Core MCP Participants

### 🖥️ Host

* The **AI-powered application**
* Example: IDE, chat app, agent framework
* Owns the **user interaction**

---

### 🔌 Client

* Lives inside the **Host**
* Speaks MCP
* Requests tools/data from servers
* Translates AI intent → MCP calls

---

### 🗄️ Server

* Exposes **tools, data, or capabilities**
* Examples:

  * Calendar server
  * File system server
  * Database server
* Responds using MCP rules

---

### 📊 Architecture (Mental Model)

```
User
 ↓
Host (AI App)
 ↓
MCP Client
 ↓
MCP Server(s)
 ↓
External Tools / Data
```

---

## What MCP Is NOT

❌ Not a model
❌ Not an LLM
❌ Not a database
❌ Not a framework

✅ It’s a **communication contract**

---

## MCP vs Prompt Engineering

| Aspect         | Prompting | MCP |
| -------------- | --------- | --- |
| Static context | ✅         | ❌   |
| Dynamic data   | ❌         | ✅   |
| Tool execution | ❌         | ✅   |
| Standardized   | ❌         | ✅   |
| Scales to apps | ❌         | ✅   |

---

## Real-World Example

> “Show me my meetings today”

Without MCP:

* Model guesses ❌

With MCP:

1. AI decides it needs calendar data
2. MCP Client calls Calendar Server
3. Calendar data returned
4. AI responds accurately ✅ 

---

## Why MCP Matters (Exam Gold ⭐)

* Enables **agentic AI**
* Makes AI **context-aware**
* Decouples AI from data sources
* Encourages **tool reuse**
* Prevents vendor lock-in

---

## One-Sentence Revision Hook

> **MCP standardizes how AI apps securely discover, request, and use external tools and data.**

---

