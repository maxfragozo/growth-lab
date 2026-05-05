# AI-Assisted Development Environment Setup

## Overview

This repository documents the setup of an AI-assisted development environment using Cursor IDE, Claude Code, Codex, and GitHub.

The goal was not only to install the required tools, but to understand how they interact and how they can be used to build and iterate faster.

---

## Tools Installed

- Cursor IDE  
- Claude Code (Anthropic official extension)  
- Codex (OpenAI official extension)  
- Git  
- GitHub  

---

## Setup Process

### 1. Research

Since I was not previously familiar with Cursor, I started by researching:
- what Cursor is  
- how it differs from traditional editors like VS Code  
- how it integrates AI into the development workflow  

This helped me approach the setup with a clearer mental model.

---

### 2. Installing Cursor and Extensions

- Installed Cursor IDE  
- Searched and installed:
  - Claude Code (Anthropic)
  - Codex (OpenAI)

Given the number of similar extensions, I verified that both were official versions to ensure reliability and correct integration.

---

### 3. Git and GitHub Setup

Although I already had a GitHub account, I had not worked directly with Git locally before.

Steps:
- Installed Git  
- Researched how Git (local version control) and GitHub (remote repository hosting) interact  
- Configured Git locally  
- Created a new public repository on GitHub  

---

### 4. Connecting the Workflow

- Opened the repository inside Cursor  
- Created this README.md file  
- Staged, committed, and pushed changes to GitHub  

This established a full workflow:
Local environment (Cursor + Git) → Version control → Remote repository (GitHub)

---

## Challenges & Solutions

### Understanding Git vs GitHub

**Challenge:**  
Initially unclear how Git and GitHub differ and interact.

**Solution:**  
Researched their roles:
- Git → local version control  
- GitHub → remote hosting and collaboration  

This clarified the workflow and made the setup more intentional.

---

### Identifying Official Extensions

**Challenge:**  
Multiple similarly named extensions in Cursor.

**Solution:**  
Verified publishers (OpenAI, Anthropic) before installing to avoid unofficial or unreliable versions.

---

### First Local Repository Workflow

**Challenge:**  
No prior hands-on experience with local Git workflows.

**Solution:**  
Followed step-by-step tutorials and practiced:
- initializing  
- committing  
- pushing  

This helped me understand the full cycle rather than just completing the task.

---

### Configuring Git Identity for Commits

**Challenge:**  
When attempting to commit and push changes from Cursor to GitHub, Git required user identity configuration.

**Solution:**  
I researched how Git handles authentication and learned that I needed to configure my global username and email.

I executed:

```bash
git config --global user.name "my-github-username"
git config --global user.email "my-email"

---

## Additional Setup & Troubleshooting

### Using AI to Support the Process

Throughout the setup, I relied on AI tools to troubleshoot issues and accelerate learning, including:
- Cursor’s built-in AI (Claude Code and Codex)
- ChatGPT

These tools helped me clarify concepts, debug issues, and understand how different components of the workflow interact.

---

## Key Takeaways

- AI tools like Cursor significantly reduce friction in building and iterating  
- Understanding the underlying workflow (Git + GitHub) is critical, not just installing tools  
- Verifying sources and tools is an important step when working with fast-moving AI ecosystems  

---

## Next Steps

- Build small AI-assisted tools (e.g., marketing or growth-related utilities)  
- Use this environment to prototype ideas quickly  
- Document experiments and iterations directly in repositories  

---

## Notes

This setup is the foundation for a workflow focused on rapid experimentation, structured thinking, and continuous iteration.
