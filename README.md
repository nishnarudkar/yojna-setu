# YojnaSetu - AI for Bharat Hackathon

> **Bridging Citizens to Government Schemes through Multilingual AI**

YojnaSetu is a voice-first, multilingual AI system that helps Indian citizens discover and access government schemes through natural conversation. Built for the "AI for Bharat" hackathon.

## 🎯 Problem Statement

Citizens across India struggle to discover government schemes due to:
- **Language barriers** preventing access to scheme information
- **Complex eligibility criteria** that are difficult to understand  
- **Lack of centralized discovery** mechanisms
- **Limited digital literacy** in target demographics

## 🚀 Solution Overview

YojnaSetu uses conversational AI to:
- **Understand natural speech** in 5 Indian languages (Hindi, English, Tamil, Telugu, Bengali)
- **Infer eligibility** from conversational input without forms
- **Handle uncertainty** and incomplete information intelligently
- **Provide personalized recommendations** with clear explanations

## 🧠 Why AI is Essential

Traditional rule-based systems cannot handle:
- **Natural language complexity**: "My husband passed away last year, I have two children and work part-time cleaning houses"
- **Contextual inference**: Understanding that "my roof leaks during monsoon" implies housing scheme eligibility
- **Multilingual processing**: Code-switching like "Mera income bahut kam hai, around 15000 per month"
- **Uncertainty handling**: Making probabilistic inferences from incomplete information

## 🏗️ System Architecture

```
┌─────────────────┐    ┌──────────────────────┐    ┌─────────────────────┐
│   Voice/Text    │───▶│  Language & Speech   │───▶│  Eligibility        │
│   Interface     │    │  Intelligence        │    │  Inference Engine   │
└─────────────────┘    └──────────────────────┘    └─────────────────────┘
                                │                            │
                                ▼                            ▼
┌─────────────────┐    ┌──────────────────────┐    ┌─────────────────────┐
│   Response &    │◀───│  Scheme Knowledge    │◀───│  User Profile       │
│   Explanation   │    │  Base                │    │  Management         │
└─────────────────┘    └──────────────────────┘    └─────────────────────┘
```

## 📋 Key Features

- **🎤 Voice-First Interface**: Hands-free operation for users with limited digital literacy
- **🌐 Multilingual Support**: Hindi, English, Tamil, Telugu, Bengali with cultural context
- **🤖 Intelligent Matching**: AI-powered eligibility inference beyond simple rules
- **📊 Confidence Scoring**: Transparent uncertainty communication
- **📱 Progressive Web App**: Works on any device with internet connectivity
- **🔒 Privacy-First**: Minimal data collection with user consent

## 📁 Project Structure

```
.kiro/specs/yojna-setu/
├── requirements.md     # Detailed system requirements with acceptance criteria
├── design.md          # Technical architecture and AI model specifications  
└── tasks.md           # Implementation roadmap with 40+ actionable tasks
```

## 🛠️ Technology Stack

- **Backend**: Python, FastAPI, SQLite
- **Frontend**: React, TypeScript, Progressive Web App
- **AI/ML**: 
  - Multilingual BERT for NLU
  - Web Speech API + Cloud Speech Services
  - Scikit-learn for eligibility classification
  - XGBoost for scheme ranking
- **Deployment**: Docker, Cloud hosting

## 📊 Success Metrics (Hackathon Demo)

- **70%+ accuracy** in scheme eligibility matching
- **5-7 minute** average interaction completion
- **80%+ speech recognition** accuracy under demo conditions
- **50+ concurrent users** support during demonstration
- **5 languages** fully supported

## 🚀 Getting Started

### 1. Review the Specification
- Read [`requirements.md`](.kiro/specs/yojna-setu/requirements.md) for detailed requirements
- Study [`design.md`](.kiro/specs/yojna-setu/design.md) for technical architecture
- Check [`tasks.md`](.kiro/specs/yojna-setu/tasks.md) for implementation roadmap

### 2. Development Setup
```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/yojna-setu.git
cd yojna-setu

# Follow Task 1 in tasks.md to set up the development environment
```

### 3. Implementation Approach
The implementation follows a bottom-up approach:
1. **Data Layer** → Scheme database and models
2. **AI Engine** → Eligibility inference and language processing  
3. **User Interface** → Voice-first web application
4. **Integration** → End-to-end system testing

## 🎯 Hackathon Goals

- **Demonstrate AI Innovation**: Show meaningful AI beyond simple chatbots
- **Solve Real Problems**: Address genuine barriers to government scheme access
- **Scalable Architecture**: Design for future expansion to production scale
- **Social Impact**: Enable better welfare distribution and citizen empowerment

## 🤝 Contributing

This project is developed for the "AI for Bharat" hackathon. The specification provides a complete roadmap for implementation.

## 📄 License

MIT License - Built for social impact and open collaboration.

---

**Built with ❤️ for AI for Bharat Hackathon**

*Empowering citizens through intelligent technology*