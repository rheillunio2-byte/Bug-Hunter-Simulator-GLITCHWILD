# 🤝 Contributing to Bug Hunter Simulator: GLITCHWILD

Thank you for your interest in contributing to **Bug Hunter Simulator: GLITCHWILD**!

Bug Hunter Simulator is an interactive debugging game designed to make programming education more engaging through missions, challenges, achievements, and game-inspired mechanics.

Contributions are welcome, whether you want to improve the interface, introduce new debugging challenges, fix issues, or suggest new features.

This guide explains how to contribute to the project.

---

## 📋 Table of Contents

- [Getting Started](#-getting-started)
- [Development Setup](#-development-setup)
- [Project Structure](#-project-structure)
- [Ways to Contribute](#-ways-to-contribute)
- [Adding Debugging Challenges](#-adding-debugging-challenges)
- [Code Guidelines](#-code-guidelines)
- [Testing](#-testing)
- [Reporting Bugs](#-reporting-bugs)
- [Suggesting Features](#-suggesting-features)
- [Pull Request Process](#-pull-request-process)
- [Commit Message Guidelines](#-commit-message-guidelines)
- [Code of Conduct](#-code-of-conduct)

---

## 🚀 Getting Started

Before contributing, make sure you have:

- Basic knowledge of HTML, CSS, and JavaScript.
- Visual Studio Code or another code editor.
- Git installed on your computer.
- A modern web browser.
- Familiarity with GitHub repositories and pull requests.

No backend setup, package installation, or API configuration is required for the current frontend version.

---

## 💻 Development Setup

**1. Fork the repository**

Visit the GitHub repository and click the **Fork** button.

**2. Clone your fork**

```bash
git clone https://github.com/YOUR-USERNAME/BugHunterSimulator.git
```

**3. Navigate to the project directory**

```bash
cd BugHunterSimulator
```

**4. Open the project in VS Code**

```bash
code .
```

**5. Start the application**

Open `index.html` using Live Server.

You can also open the file directly in your browser.

**6. Create a new branch**

```bash
git checkout -b feature/your-feature-name
```

---

## 📂 Project Structure

```text
BugHunterSimulator/
│
├── index.html
├── styles.css
├── app.js
├── README.md
├── CONTRIBUTING.md
├── LICENSE
│
└── images/
```

Keep code organized and avoid placing unrelated features in a single file.

- `index.html`: Main application structure.
- `styles.css`: Visual design, layout, and animations.
- `app.js`: Game logic, challenge handling, and interactions.
- `README.md`: Project documentation.
- `CONTRIBUTING.md`: Contribution guidelines.
- `LICENSE`: Project licensing information.
- `images/`: Screenshots and project assets.

---

## 🛠️ Ways to Contribute

### 1. Report Bugs

Help identify and resolve problems involving:

- Incorrect game behavior.
- Broken buttons or navigation.
- Incorrect XP calculations.
- Progress-saving issues.
- Challenges that produce incorrect results.
- Visual glitches and layout problems.
- Browser compatibility issues.

### 2. Improve the User Interface

Suggestions include:

- More interactive game elements.
- Better animations and transitions.
- Improved responsive layouts.
- More distinctive mission screens.
- Better visual feedback.
- Accessibility improvements.

Maintain the GLITCHWILD identity when introducing new designs.

### 3. Add Debugging Challenges

Contributors can suggest new programming challenges involving:

- Syntax errors.
- Logical errors.
- Incorrect conditions.
- Loops and iteration.
- Functions.
- Lists and arrays.
- String manipulation.
- Variables and data types.

Every challenge should have a clear objective, correct answer, and explanation.

### 4. Improve Game Mechanics

Possible improvements include:

- New mission types.
- Boss encounters.
- Hunter progression.
- Additional achievements.
- Daily missions.
- Unlockable rewards.
- New simulation environments.

---

## 🪲 Adding Debugging Challenges

When creating a new challenge, make sure it follows these guidelines:

**Challenge requirements:**

1. Provide a clear challenge title.
2. Include the difficulty level.
3. Identify the programming concept.
4. Present the code or problem.
5. Define the expected answer.
6. Provide a short explanation.
7. Ensure the answer is technically correct.

**Example challenge concept:**

```python
numbers = [1, 2, 3, 4, 5]

for number in numbers:
    print(numbers[number])
```

**Problem:** Identify why the code produces an indexing error.

**Expected explanation:** The loop variable contains each element's value, not its index. Accessing `numbers[number]` eventually attempts to access an index outside the list.

Challenges should be educational, accurate, and appropriate for their assigned difficulty.

---

## 📝 Code Guidelines

### HTML
- Use semantic HTML elements whenever possible.
- Keep the document structure organized.
- Use descriptive class and ID names.
- Maintain accessibility with appropriate labels and attributes.

### CSS
- Use consistent naming conventions.
- Keep styles organized by component or section.
- Prefer reusable classes.
- Maintain responsive behavior.
- Avoid unnecessary animations that negatively affect usability.
- Respect reduced-motion preferences.

### JavaScript
- Use clear and descriptive variable names.
- Prefer `const` and `let` over `var`.
- Use functions to separate different game mechanics.
- Avoid unnecessary global variables.
- Validate user inputs.
- Handle unexpected values and errors.
- Keep localStorage operations organized and defensive.

### General Guidelines
- Write readable and maintainable code.
- Avoid unnecessary dependencies.
- Remove unused code.
- Do not introduce API keys, passwords, or private credentials.
- Preserve existing gameplay functionality when modifying the interface.

---

## 🧪 Testing

Before submitting a contribution, test your changes.

### Functional Testing
- Verify that buttons and navigation work.
- Check challenge answers and explanations.
- Test XP and progression calculations.
- Verify hints and lives.
- Check achievement conditions.
- Confirm that supported progress-saving features work.

### Interface Testing
- Test the application on desktop and mobile screen sizes.
- Check hover and active states.
- Verify animations and transitions.
- Ensure text remains readable.
- Check that interface elements do not overlap.

### Browser Testing
Test using modern versions of:
- Google Chrome
- Microsoft Edge
- Mozilla Firefox

Also check the browser developer console for JavaScript errors.

---

## 🐛 Reporting Bugs

If you discover a problem, create a GitHub Issue.

Include:

- A clear issue title.
- A description of the problem.
- Steps to reproduce the issue.
- Expected behavior.
- Actual behavior.
- Browser and operating system.
- Screenshots or recordings, if applicable.

Use the following format:

**Title:** [BUG] Brief description of the issue

**Description:**
Explain what happened.

**Steps to Reproduce:**
1. Open the game.
2. Navigate to the affected feature.
3. Perform the action.
4. Observe the problem.

**Expected Result:**
Describe what should happen.

**Actual Result:**
Describe what happened instead.

---

## 💡 Suggesting Features

Feature suggestions are welcome!

When submitting a suggestion, include:

- Feature name.
- Description.
- Purpose and expected benefits.
- How it could work.
- Optional screenshots or references.

Examples:
- New debugging mission categories.
- Additional simulation worlds.
- More interactive boss battles.
- Customizable hunter profiles.
- New achievement systems.

---

## 🔀 Pull Request Process

1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Test the application.
5. Commit your changes with a clear message.
6. Push your branch to your fork.
7. Open a Pull Request.
8. Explain what you changed and why.
9. Wait for review and address feedback.

### Pull Request Checklist

Before submitting, make sure:

- [ ] The changes have been tested.
- [ ] Existing features still work.
- [ ] The code follows the project's guidelines.
- [ ] No unnecessary files or dependencies were added.
- [ ] No API keys or private information are included.
- [ ] Documentation has been updated when necessary.
- [ ] Screenshots are provided for significant UI changes.

---

## 📝 Commit Message Guidelines

Use short, descriptive commit messages.

Recommended prefixes:

| Prefix | Purpose |
|---|---|
| `feat:` | New feature |
| `fix:` | Bug fix |
| `style:` | UI or styling changes |
| `docs:` | Documentation updates |
| `refactor:` | Code restructuring |
| `test:` | Testing-related changes |
| `perf:` | Performance improvements |

Examples:

```bash
git commit -m "feat: add new debugging missions"
git commit -m "fix: correct XP calculation"
git commit -m "style: improve mission animations"
git commit -m "docs: update README"
```

---

## 🤝 Code of Conduct

All contributors are expected to:

- Be respectful and professional.
- Provide constructive feedback.
- Respect other contributors' work.
- Avoid discriminatory or inappropriate behavior.
- Focus on improving the project.
- Help maintain a welcoming learning environment.

---

## 📬 Questions and Support

For questions, suggestions, or project-related concerns, you may open a GitHub Issue or contact the project developer through GitHub.

**GitHub:** [@rheillunio2-byte](https://github.com/rheillunio2-byte)

---

Thank you for helping improve **Bug Hunter Simulator: GLITCHWILD**!

Every contribution helps make debugging more interactive, educational, and fun.

**Hunt the errors. Restore the simulation. Become the ultimate Bug Hunter.** 🪲