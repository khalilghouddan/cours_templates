# 🎓 AI Course Generation - Template Library

This directory contains a standardized set of **12 Educational Templates** designed to power the automated generation of high-quality, pedagogically sound courses. These templates serve as the architectural blueprint for the AI generator, ensuring consistency in depth, style, and structure across different learning models and durations.

---

## 🏗️ Template Categories

The library is organized into three primary pedagogical models, each tailored to a specific learning objective:

### 1. **Concept-Based (Theory & Foundations)**
*   **Focus**: Building mental models, understanding terminology, and historical/theoretical context.
*   **Best for**: Introductions to new fields, academic training, and conceptual mastery.
*   **Structure**: Heavily emphasizes theoretical frameworks, relationship analysis, and emerging research.

### 2. **Skill-Based (Practical & Hands-On)**
*   **Focus**: Tool mastery, technical workflows, and project execution.
*   **Best for**: Software engineering, design, data science, and technical bootcamps.
*   **Structure**: Centers on guided practice, environment setup, mini-projects, and portfolio building.

### 3. **Problem-Solution (Strategic & Analytical)**
*   **Focus**: Critical thinking, business diagnostics, and executive decision-making.
*   **Best for**: Leadership training, business strategy, consulting, and operational problem-solving.
*   **Structure**: Utilizes scenario-based learning, root cause analysis, and strategic optimization workshops.

---

## ⏱️ Duration Scaling

Each model is provided in four distinct durations to accommodate different learner commitment levels:

| Duration | Intent | Typical Structure |
| :--- | :--- | :--- |
| **2 Hours** | **Quick Start** | 4 Chapters, foundational focus, rapid assessment. |
| **4 Hours** | **Guided Learning** | 5 Chapters, balanced theory and practice. |
| **8 Hours** | **Deep Dive** | 5-6 Chapters, detailed case studies or advanced labs. |
| **20 Hours** | **Mastery / Bootcamp** | 6+ Chapters, intensive projects, and professional validation. |

---

## 📄 File Schema

All templates follow a strict JSON-compatible structure to ensure seamless integration with the AI pipeline:

```json
{
  "id": "Template_ID_Xh",
  "template_type": "concept_based | skill_based | problem_solution",
  "description": "High-level summary of the template's pedagogical intent.",
  "learning_goal": "The overarching objective for the learner.",
  "domains": ["ai", "business", "..."],
  "duration_min": 10,
  "duration_max": 20,
  "levels": ["beginner", "intermediate", "advanced"],
  "teaching_styles": ["theory_based", "hands_on", "scenario_based"],
  "recommended_for": ["Use cases"],
  "course_structure": [
    {
      "chapter_order": 1,
      "chapter_type": "...",
      "chapter_title": "...",
      "duration_minutes": 60,
      "learning_goal": "...",
      "must_contain": ["Key topics"],
      "lessons": [
        {
          "lesson_type": "...",
          "purpose": "...",
          "must_contain": ["Content requirements"]
        }
      ],
      "quiz": {
        "purpose": "...",
        "must_test": ["Assessment targets"]
      }
    }
  ]
}
```

---

## 🚀 Usage

These templates are ingested by the **AI Course Generator** to:
1.  Define the **Chapter Roadmap**.
2.  Set **Time Constraints** for content generation.
3.  Enforce **Pedagogical Requirements** (must_contain fields).
4.  Standardize **Assessment Strategies**.

---
*Last Updated: May 2026*
