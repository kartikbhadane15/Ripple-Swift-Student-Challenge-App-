# 🌊 Ripple
### *Every choice shapes something.*

Ripple is a cinematic, experience-driven app built for the 
Apple Swift Student Challenge 2026. It helps children understand 
responsibility — not through instruction, but through consequence.

---

## 🎯 Concept

Children are constantly told what's right and wrong.
But responsibility isn't formed by being told.
It's formed by making choices and living with their outcomes.

Ripple creates a safe space where you navigate three everyday moments:
- 💰 **Money** — How will you use what you've earned?
- 🧾 **Honesty** — Will you tell the truth when it's hard?
- 💙 **Empathy** — Will you reach out to someone who needs you?

Every decision creates a ripple through your world.
No scores. No judgment. Just consequence.

Three years later — the world reflects the person 
your choices practiced.

---

## ✨ Features

- 🎬 Cinematic scene transitions with custom BlurFade animations
- 🌊 Expanding ripple animations built in SpriteKit
- 🎨 Real-time environment color shifts based on your choices
- 🔊 10+ layered audio tracks that shift with emotional tone
- ⏩ Warp speed fast-forward transition to the future
- 🌟 CoreImage Gaussian glow effects for consequence rendering
- 📖 Typewriter text animations throughout
- 🔄 Full replay system with fresh state reset

---

## 🛠 Built With

| Technology | Purpose |
|---|---|
| SwiftUI | UI, transitions, animations |
| SpriteKit | Game scenes, ripple effects, physics |
| AVFoundation | Layered audio management |
| CoreImage | Glow and blur visual effects |
| Gemini API | AI-generated visual assets |
| Suno AI | AI-generated music and ambient audio |

---

## 📱 Requirements

- iOS 16.0+
- Xcode 15+
- Swift 5.9+

---

## 🗂 Project Structure
```
Ripple.swiftpm/
├── Models/
│   └── RippleState.swift         # Tracks all 3 choices
├── Controllers/
│   ├── AudioManager.swift        # Layered audio system
│   ├── ComfortDecisionScene.swift # Money scene
│   ├── HonestyExperienceScene.swift # Honesty scene
│   ├── EmpathyExperienceScene.swift # Empathy scene
│   ├── ThreeYearsLaterScene.swift  # Consequence scene
│   └── BirdScene.swift
├── Views/
│   ├── ContentView.swift         # App phase management
│   ├── CharacterIntroView.swift
│   ├── ComfortDecisionView.swift
│   ├── HonestyExperienceView.swift
│   ├── EmpathyExperienceView.swift
│   ├── FastForwardView.swift     # Warp transition
│   ├── ThreeYearsLaterView.swift
│   ├── FadeIn.swift
│   ├── GradientText.swift
│   └── StoryText.swift
```

---

## 🎭 Emotional Arc
```
Comfort → Discomfort → Identity Realization
```

| Scene | Theme | What Changes |
|---|---|---|
| Decision 1 | Money | What you have |
| Decision 2 | Honesty | How others see you |
| Decision 3 | Empathy | Who you are |
| 3 Years Later | Identity | Who you became |

---

## 🏆 Submission

Built for **Apple Swift Student Challenge 2026**

> *"Responsibility is not taught. It is lived."*

---

## 👨‍💻 Author

**Kartik** — Swift Developer & Designer
Pune, India 🇮🇳
