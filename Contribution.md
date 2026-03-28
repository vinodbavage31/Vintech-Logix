<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=160&section=header&text=Contributing%20to%20Vintech%20Logix&fontSize=40&fontColor=ffffff&animation=fadeIn&fontAlignY=45&desc=Thank%20you%20for%20being%20here.%20Every%20contribution%20counts.&descAlignY=68&descAlign=50&descSize=16&descColor=a78bfa"/>

<br/>

<img src="https://img.shields.io/badge/Contributions-Welcome-a78bfa?style=for-the-badge&logo=github&logoColor=white"/>
<img src="https://img.shields.io/badge/PRs-Open-6d28d9?style=for-the-badge"/>
<img src="https://img.shields.io/badge/First%20Timers-Friendly-22c55e?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Code%20of%20Conduct-Enforced-e34f26?style=for-the-badge"/>

<br/><br/>

> *"Great software is never built alone. It is built by communities of people who care."*

<br/>

</div>

---

## Table of Contents

<details>
<summary><b>Click to expand</b></summary>

- [Welcome](#-welcome)
- [Code of Conduct](#-code-of-conduct)
- [What Can I Contribute?](#-what-can-i-contribute)
- [Before You Start](#-before-you-start)
- [Setting Up the Project Locally](#-setting-up-the-project-locally)
- [Branching Strategy](#-branching-strategy)
- [Commit Message Guide](#-commit-message-guide)
- [How to Submit a Pull Request](#-how-to-submit-a-pull-request)
- [PR Review Process](#-pr-review-process)
- [Reporting Bugs](#-reporting-bugs)
- [Suggesting Features](#-suggesting-features)
- [Contribution Ideas by Skill Level](#-contribution-ideas-by-skill-level)
- [Style Guide](#-style-guide)
- [What NOT to Do](#-what-not-to-do)
- [Recognition](#-recognition)
- [Need Help?](#-need-help)

</details>

---

<div align="center">

## Welcome

<img src="https://media.giphy.com/media/du3J3cXyzhj75IOgvA/giphy.gif" width="420" alt="Open source collaboration"/>

</div>

<br/>

First of all — **thank you for taking the time to contribute to Vintech Logix.**

Whether you're fixing a single typo, redesigning a whole section, improving performance, or just opening an issue with a thoughtful suggestion — **it all matters**. This project is being built in the open, and every person who shows up makes it better.

Vintech Logix is the official website of a future digital services company. It's built with pure **HTML and CSS** — deliberately lean, fast, and accessible. If you believe in the open web and want to help shape something real from the ground up, you're in the right place.

---

<div align="center">

## Code of Conduct

</div>

By participating in this project, you agree to uphold the following standards in all interactions — issues, pull requests, discussions, and code reviews:

| Principle | What It Means |
|---|---|
| **Be respectful** | Treat every contributor with kindness, regardless of skill level or background |
| **Be constructive** | Criticism is welcome — cruelty is not. Critique the code, not the person |
| **Be inclusive** | This project welcomes contributors of all backgrounds, nationalities, and experience levels |
| **Be honest** | If something is broken or wrong, say so clearly. Honesty builds trust |
| **Be patient** | Reviews take time. Maintainers are people too |

Behaviour that violates these principles — harassment, discrimination, or deliberate hostility — will result in being permanently removed from the project.

---

<div align="center">

## What Can I Contribute?

</div>

You don't need to be a senior developer to contribute. Here is every type of contribution that is genuinely valuable to this project:

### Design & Frontend

- Improve the overall layout, spacing, or visual balance of any page
- Refine or add CSS animations, transitions, and hover effects
- Improve the hero section, navigation, footer, or any existing component
- Suggest or implement a better colour palette or typography system
- Build new sections — Services, Portfolio, Testimonials, Contact, etc.

### Performance & SEO

- Reduce page weight — optimise images, clean up unused CSS
- Improve semantic HTML structure for better accessibility and SEO
- Add or fix meta tags, Open Graph tags, and structured data
- Audit and improve Lighthouse scores (Performance, Accessibility, SEO, Best Practices)

### Responsiveness

- Improve the layout on mobile (320px–768px)
- Fix any overflow, alignment, or spacing issues on tablet screens
- Ensure all interactive elements are touch-friendly

### Documentation

- Improve this CONTRIBUTING guide or the main README
- Add comments to HTML and CSS explaining complex sections
- Write a proper `LICENSE` file if missing
- Create a `CHANGELOG.md` to track project history

### Accessibility

- Add ARIA roles and labels to interactive elements
- Improve keyboard navigation flow
- Ensure colour contrast meets WCAG 2.1 AA standards
- Add `alt` text to all images

### Bug Fixes

- Fix broken layouts, alignment issues, or visual regressions
- Correct typos in any page content
- Fix broken links

---

<div align="center">

## Before You Start

</div>

Before writing any code, please:

1. **Search existing issues** — your idea or bug may already be reported. Avoid duplicates.
2. **Open an issue first** — for any non-trivial change (new section, major redesign, new feature), open an issue and describe what you want to do. This prevents wasted effort and ensures alignment.
3. **Wait for acknowledgement** — once the maintainer (Vinod) confirms the approach, then start building.
4. **Keep it focused** — one PR should do one thing. A PR that fixes a bug AND redesigns the navbar AND adds a new section is very hard to review. Split it up.

> For small fixes (typos, broken links, minor CSS tweaks) — you can go straight to a PR without opening an issue first.

---

<div align="center">

## Setting Up the Project Locally

</div>

This project requires **zero build tools**, **zero npm**, and **zero configuration**. That's by design.

**Step 1 — Fork the Repository**

Go to [github.com/vinodbavage31/Vintech-Logix](https://github.com/vinodbavage31/Vintech-Logix) and click **Fork**.

**Step 2 — Clone Your Fork**

```bash
git clone https://github.com/YOUR-USERNAME/Vintech-Logix.git
cd Vintech-Logix
```

**Step 3 — Open in Your Editor**

```bash
code .
```

**Step 4 — View in a Browser**

Since it's pure HTML/CSS, just open the file directly in your browser:

```bash
# Option A — open directly
open index.html

# Option B — use VS Code Live Server extension (recommended)
# Right-click index.html → "Open with Live Server"
```

> **Recommended:** Install the [Live Server extension](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) for VS Code. It auto-refreshes the browser on every file save — makes development much smoother.

**Step 5 — Make Your Changes and Verify**

Edit files, check the result in the browser, and make sure nothing is broken before committing.

---

<div align="center">

## Branching Strategy

</div>

Always create a new branch for your work. Never commit directly to `main`.

```bash
# Create and switch to a new branch
git checkout -b type/short-description

# Branch naming examples:
git checkout -b feature/services-section
git checkout -b fix/mobile-nav-overflow
git checkout -b style/hero-typography
git checkout -b docs/update-readme
git checkout -b perf/optimise-images
git checkout -b a11y/add-aria-labels
```

| Prefix | Use For |
|---|---|
| `feature/` | New sections, new components, new functionality |
| `fix/` | Bug fixes, broken layouts, visual regressions |
| `style/` | Visual-only changes — colours, fonts, spacing |
| `docs/` | README, CONTRIBUTING, comments, documentation |
| `perf/` | Performance improvements, image optimisation |
| `a11y/` | Accessibility improvements |
| `seo/` | Meta tags, semantic HTML, structured data |

---

<div align="center">

## Commit Message Guide

</div>

Clear commit messages make the project history readable and maintainable. Follow this format:

```
type: short description in present tense (max 72 chars)

Optional body — explain WHY the change was made if it's not obvious.
```

**Type prefixes:**

| Type | When to Use |
|---|---|
| `feat` | Adding something new |
| `fix` | Fixing a bug or broken behaviour |
| `style` | CSS/visual changes with no functional impact |
| `docs` | Documentation only changes |
| `perf` | Performance improvements |
| `refactor` | Code restructuring without changing behaviour |
| `a11y` | Accessibility improvements |
| `chore` | Maintenance tasks, file cleanup |

**Good examples:**

```bash
git commit -m "feat: add services section with card grid layout"
git commit -m "fix: resolve horizontal scroll on mobile navbar"
git commit -m "style: update hero section font to Inter"
git commit -m "docs: add setup instructions to CONTRIBUTING.md"
git commit -m "a11y: add alt text to all images in index.html"
git commit -m "perf: compress hero background image by 60%"
```

**Bad examples:**

```bash
git commit -m "fixed stuff"
git commit -m "changes"
git commit -m "update"
git commit -m "asdfgh"
```

---

<div align="center">

## How to Submit a Pull Request

</div>

Once your changes are ready:

**1. Stage and commit your work**

```bash
git add .
git commit -m "feat: add contact form section"
```

**2. Push your branch to your fork**

```bash
git push origin feature/contact-form
```

**3. Open the Pull Request**

- Go to your forked repository on GitHub
- Click **"Compare & pull request"**
- Make sure the base is `vinodbavage31/Vintech-Logix` and the target branch is `main`

**4. Fill out the PR description properly**

A good PR description includes:

```
## What does this PR do?
Adds a fully responsive contact form section to the homepage.

## Why?
The website currently has no way for visitors to reach out.

## Screenshots (if visual changes)
[attach before/after screenshots]

## Checklist
- [x] Tested in Chrome, Firefox, and mobile
- [x] No broken layouts
- [x] No unnecessary files included
- [x] Commit messages follow the guide
```

**5. Link any related issue**

If this PR resolves an existing issue, add this to the description:

```
Closes #12
```

---

<div align="center">

## PR Review Process

</div>

After you submit a pull request, here is what happens:

| Step | What to Expect |
|---|---|
| **Automated checks** | GitHub will run basic checks on your PR |
| **Initial review** | Vinod (or a collaborator) will review within a few days |
| **Feedback** | You may receive comments or change requests — this is normal and not personal |
| **Revision** | Make the requested changes, push to the same branch, and the PR updates automatically |
| **Approval & merge** | Once approved, the PR will be merged into `main` |

> **Be patient.** Maintainers review PRs in their own time. If your PR hasn't received a response within a week, you're welcome to leave a polite comment asking for an update.

---

<div align="center">

## Reporting Bugs

</div>

Found something broken? Please [open an issue](https://github.com/vinodbavage31/Vintech-Logix/issues/new) and include the following:

```
**Bug Description**
A clear description of what is wrong.

**Steps to Reproduce**
1. Open index.html in Chrome
2. Resize window to mobile width
3. Notice the navbar overflows horizontally

**Expected Behaviour**
The navbar should collapse or wrap cleanly on mobile.

**Actual Behaviour**
A horizontal scrollbar appears and the layout breaks.

**Environment**
- Browser: Chrome 122 / Firefox 123 / Safari 17
- OS: Windows 11 / macOS Sonoma / Android 14
- Screen size: 375px (iPhone SE)

**Screenshots**
[attach if applicable]
```

The more detail you provide, the faster it gets fixed.

---

<div align="center">

## Suggesting Features

</div>

Have an idea for a new section, feature, or improvement? [Open a feature request](https://github.com/vinodbavage31/Vintech-Logix/issues/new) and describe:

- **What** you want to add or change
- **Why** it would improve the project
- **How** you'd approach it (if you have thoughts)
- Any **references or examples** from other sites you admire

Feature requests are reviewed regularly. The best ones get added to the roadmap.

---

<div align="center">

## Contribution Ideas by Skill Level

</div>

### Beginner — Good First Issues

These are great if this is your first open-source contribution:

| Task | Area |
|---|---|
| Fix a typo or grammar error anywhere on the site | Content |
| Add `alt` attributes to images that are missing them | Accessibility |
| Add a `<meta description>` tag to a page | SEO |
| Improve line spacing or paragraph readability | CSS |
| Add a smooth scroll behaviour using CSS | CSS |
| Add a `title` attribute to links | HTML |

### Intermediate

| Task | Area |
|---|---|
| Build a responsive services card grid | HTML/CSS |
| Add a sticky header that changes style on scroll | CSS |
| Create a mobile-friendly hamburger menu (CSS only) | CSS |
| Implement CSS custom properties for theming | CSS |
| Add Open Graph and Twitter Card meta tags | SEO |
| Build a clean footer with links and social icons | HTML/CSS |
| Improve the hero section with animated text | CSS |

### Advanced

| Task | Area |
|---|---|
| Implement a full CSS dark/light mode toggle | CSS |
| Build a CSS-only testimonials carousel | CSS |
| Add scroll-triggered reveal animations using `@keyframes` | CSS |
| Create a complete CSS design token system | CSS |
| Achieve a 100/100 Lighthouse score across all metrics | Performance |
| Add full keyboard navigation support | Accessibility |

---

<div align="center">

## Style Guide

</div>

To keep the codebase consistent, please follow these conventions:

### HTML

```html
<!-- Use semantic elements -->
<header>, <nav>, <main>, <section>, <article>, <footer>

<!-- Use meaningful class names (BEM-style preferred) -->
<div class="services-card">
<p class="services-card__description">

<!-- Always include alt text on images -->
<img src="hero.jpg" alt="Vintech Logix hero banner"/>

<!-- Use lowercase for all tags and attributes -->
<a href="#" class="btn-primary">Get Started</a>
```

### CSS

```css
/* Group properties logically */
.element {
  /* Box model */
  display: flex;
  width: 100%;
  padding: 1rem 2rem;
  margin: 0 auto;

  /* Typography */
  font-family: 'Inter', sans-serif;
  font-size: 1rem;
  color: #ffffff;

  /* Visual */
  background-color: #0f0c29;
  border-radius: 8px;
  box-shadow: 0 4px 20px rgba(0, 0, 0, 0.3);

  /* Transitions last */
  transition: all 0.3s ease;
}

/* Use CSS custom properties for repeated values */
:root {
  --color-primary: #7c3aed;
  --color-accent: #a78bfa;
  --font-main: 'Inter', sans-serif;
  --spacing-lg: 2rem;
}
```

### General

- Use **2 spaces** for indentation (not tabs)
- Keep lines under **100 characters** where possible
- Remove trailing whitespace before committing
- Do not leave commented-out blocks of dead code in your PR

---

<div align="center">

## What NOT to Do

</div>

Please avoid the following — PRs containing these will be closed without merge:

- Committing directly to `main` — always use a branch
- Including `node_modules`, `.DS_Store`, `.vscode/settings.json`, or other local/system files
- Adding JavaScript dependencies or npm packages — this project is intentionally JS-free
- Submitting AI-generated code as-is without reviewing and testing it
- Making multiple unrelated changes in a single PR — keep PRs focused
- Copying design or code from other websites without proper licensing
- Removing attribution, copyright notices, or author credits

---

<div align="center">

## Recognition

</div>

Every contributor who has a PR merged will be:

- Listed in the project's **Contributors** section on GitHub automatically
- Credited in the `CHANGELOG.md` when it is introduced
- Mentioned with appreciation in release notes

This project is being built in public from day one. The people who contribute early are the ones who will be remembered as part of the foundation.

---

<div align="center">

## Need Help?

</div>

If you're stuck, unsure about something, or just want to discuss an idea before building it:

| Channel | Use It For |
|---|---|
| [Open an Issue](https://github.com/vinodbavage31/Vintech-Logix/issues) | Questions about specific bugs or features |
| [Start a Discussion](https://github.com/vinodbavage31/Vintech-Logix/discussions) | Broad ideas, design feedback, general questions |
| [Comment on a PR](https://github.com/vinodbavage31/Vintech-Logix/pulls) | Questions about a specific contribution in review |

No question is too small. If you're new to open source and nervous about your first contribution — **just start**. Everyone here was a beginner once.

---

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=120&section=footer&text=Happy%20Contributing!&fontSize=28&fontColor=a78bfa&animation=fadeIn&fontAlignY=65"/>

**Vintech Logix** — *Built in the open. Built together.*

*© 2025 Vinod Bavage — Vintech Logix. All rights reserved.*

</div>
