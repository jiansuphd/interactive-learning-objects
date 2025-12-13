# Interactive Learning Object (ILO) Library

A collection of HTML5, CSS, and JavaScript interactions designed for higher education courseware. This repository serves as a design system and component library for creating engaging digital learning experiences.

## 📂 Project Structure

This repository is organized to separate reusable templates from specific course implementations.

- **`/templates`**: Generic, reusable versions of interactions. Use these as a starting point for new projects.
    - **`/hotspot`**: Image-based exploration activities.
    - **`/timeline`**: Interactive timelines for course mapping or history.
    - **`/checklist`**: Interactive tools for student or faculty self-checks.
    - **`/effects`**: Visual CSS effects like liquid animations.

- **`/examples`**: Real-world implementations used in specific courses.
    - **`/data101`**: Interactions for Data Science 101 (Probability Labs, AI Sims, Journey Maps).
    - **`/hbs513`**: Content for HBS513 (ITS Labs, Financial Engineering Lectures).
    - **`/hbs514`**: Content for HBS514 (Ethics Labs, Interactive Scenarios).

- **`/assets`**: Shared resources.
    - **`/css`**: Global styles (`shared.css`) and variables.
    - **`/js`**: Common utility scripts (`utils.js`).
    - **`/images`**: Shared graphical assets.

## 🚀 Getting Started

### Prerequisites
You can run these files directly in any modern web browser. No server is required for the static versions.

### Installation
1. Clone the repo:
   ```bash
   git clone [https://github.com/jiansuphd/interactive-learning-objects.git](https://github.com/jiansuphd/interactive-learning-objects.git)
````

2.  Open `index.html` in your browser. This file acts as a **gallery** launching point, allowing you to browse and access all templates and examples from a single interface.

## 🛠 Component Categories

### 1\. Visualizations

  - **Journey Maps:** SVG and HTML based timelines for course mapping.
  - **Liquid Effects:** CSS-heavy visual flourishes for engagement.

### 2\. Simulations

  - **Probability Lab:** JS-driven logic for data science concepts.
  - **AI/ML Lab:** Interactive demonstrations of artificial intelligence principles.
  - **Ethics Lab:** Branching scenario logic for decision-making exercises.

### 3\. Interactions

  - **Hotspots:** Click-to-reveal interactions for image exploration.
  - **Lesson Player:** A wrapper interface for sequential content.
  - **Interactive Checklists:** Tools for tracking progress or readiness.

## 🔮 Future Roadmap

  - [ ] Refactor CSS into SASS/SCSS modules.
  - [ ] Convert HTML templates into React/Vue components.
  - [ ] Create a JSON schema for easy content injection.
  - [ ] Publish as an NPM package for easy import into LMS platforms.

## 📄 License

[MIT](https://choosealicense.com/licenses/mit/)
