# NEXA – AI Process Coach

NEXA is an AI-powered process coach that monitors your workflow in real time and guides you through planning → coding → testing.

It detects when you are stuck, protects your flow state, celebrates milestones, and suggests the next best action while you work.

## 🚧 Project Status
⚠️ This project is currently in development and not fully optimized.  
Core features are being tested and improved.

## ✨ Features (Planned / In Progress)

- Detects when the user is stuck (>5 minutes on same file)
- Suggests actionable next steps
- Guides phase transitions (planning → implementation → testing → debugging)
- Celebrates milestones (test files, project structure)
- Protects flow state (minimal interruption during productive work)
- Real-time file monitoring using `watchdog`
- AI coaching using Anthropic API

## 🧠 How It Works

NEXA watches file activity inside a project folder and:

1. Tracks recent edits and activity patterns
2. Detects momentum states (starting, flowing, stuck, completing)
3. Identifies current development phase
4. Provides coaching messages at key moments

## 🏗️ Tech Stack

- Python
- watchdog (file system monitoring)
- Anthropic API (AI coaching)
- threading (background coaching loop)

## ⚙️ Setup (Work in Progress)

```bash
pip install anthropic watchdog
export ANTHROPIC_API_KEY="your-key"
python process_coach.py /path/to/project
# NEXA
AI process coach that monitors your workflow, detects when you're stuck, protects flow state, and guides planning → coding → testing in real time.
