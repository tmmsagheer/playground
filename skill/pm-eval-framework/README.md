# 🤖 PM Eval Framework — Custom Agent Skill

An automated repository auditing tool inspired by Aakash Gupta's viral framework: [10 Questions an AI PM Interviewer Will Ask About Your Evals](https://www.linkedin.com/posts/ai-from-aakash_10-questions-an-ai-pm-interviewer-will-ask-activity-7508948392694251522-SXUQ). 

Built using AntiGravity's plain-markdown `SKILL.md` paradigm, this tool instantly runs a **10-point Product Management evaluation audit** against your codebase's AI pipelines.

---

## 🚀 How it Works
When triggered within your AI workspace, the agent scans your repository (`eval/index.js`, Zod schemas, workflows, and commit history) to generate a beautifully structured report. It evaluates your current setup across the 10 pillars of real-world AI engineering and maps out actionable gaps.

### 📋 The 10-Point Audit Checklist
1. **Target Metric Definition:** What does a correct answer look like for your feature?
2. **Golden Set Provenance:** Where did your golden set come from?
3. **Dataset Scale & Rationale:** How big is it, and why that size?
4. **Grader Mechanism:** What does your grader actually measure?
5. **Performance Baseline:** What is your baseline threshold?
6. **Regression Logic:** What counts as a regression (breaks CI/CD)?
7. **Historical Failure Modes:** What broke when you first ran it?
8. **Operational Cadence:** How often does it run, and what happens on failure?
9. **Iterative Adjustments:** What did you change because of the result?
10. **Known Vulnerabilities:** What can your eval still not catch?

---

## 🛠️ Installation & Setup

To use this skill locally in your custom Gemini configuration workspace, save the `SKILL.md` file in the dedicated skill directory.

### 1. Create the Directory Structure
Run the following command in your terminal to create the directory path:
```bash
mkdir -p ~/.gemini/config/skills/pm-eval-framework
```

### 2. Add the Skill File
Create a `SKILL.md` file inside that directory and paste the contents of the `SKILL.md` provided in this repository.

### 3. Usage
Once configured, trigger the framework inside your repository workspace by calling:
```text
\(\pm-\)eval-framework
```
💡 *Pro Tip: Use it in conjunction with `\grill-me` to practice defending your framework choices in a mock interview environment!*

---

## 🤝 Credits
- Framework concept by [Aakash Gupta (Product Growth)](https://linkedin.com)
- Configured using the `SKILL.md` architecture popularized by AntiGravity's open-source initiatives.
