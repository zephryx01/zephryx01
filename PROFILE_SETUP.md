# Zephryx GitHub Profile — Implementation Guide

This package is designed for the GitHub account `zephryx01`.

## 1. Correct the profile positioning

Your current profile leads with **Frontend Web Developer** and describes ethical hacking as part-time. That no longer represents your strongest professional identity.

Use these profile fields:

- **Name:** `Mihir | Zephryx`
- **Bio:** `SOC Analyst & Threat Hunter | Offensive Security Practitioner | Building Zephryx`
- **Company:** `Zephryx`
- **Location:** `India`
- **Website:** `https://zephryx.in`
- **X:** `@zephryx01`
- **LinkedIn:** `https://www.linkedin.com/in/zephryx/`
- **YouTube:** `https://www.youtube.com/@Zephryx_Academy`

Keep the bio outcome-focused. Avoid labels such as “part-time hacker,” “beginner,” or a long list of unrelated technologies.

## 2. Create or update the special profile repository

The public repository must be named exactly:

```text
zephryx01
```

Its root must contain `README.md`.

Recommended structure:

```text
zephryx01/
├── .github/
│   └── workflows/
│       └── snake.yml
├── assets/
│   └── terminal-banner.svg
├── README.md
└── PROFILE_SETUP.md
```

## 3. Fastest implementation through the GitHub website

1. Open the `zephryx01/zephryx01` repository.
2. Select **Add file → Upload files**.
3. Upload the extracted files while preserving the folders.
4. Commit with:

```text
feat: redesign cybersecurity profile
```

5. Open the **Actions** tab.
6. Select **Generate contribution snake**.
7. Select **Run workflow**.
8. Wait for the workflow to finish.
9. Refresh your public profile.

The snake is generated into a separate branch named `output`.

If the workflow returns a permissions error:

1. Open **Repository Settings → Actions → General**.
2. Find **Workflow permissions**.
3. Select **Read and write permissions**.
4. Save and run the workflow again.

## 4. Local Git implementation on Windows

```powershell
cd C:\dev
git clone https://github.com/zephryx01/zephryx01.git
cd zephryx01
```

Copy the package contents into that folder, then run:

```powershell
git add .
git commit -m "feat: redesign cybersecurity profile"
git push origin main
```

## 5. Pin repositories as proof of work

Pin only repositories that reinforce your security positioning. The ideal order is:

1. **Zephryx platform or production landing page**
2. **Web enumeration playbook**
3. **SOC workflow automation**
4. **DGA analysis or domain investigation toolkit**
5. **Linux 100**
6. **Cybersecurity cheatsheets or practical labs**

Do not pin empty, duplicate, tutorial-copy, or abandoned repositories merely to fill all six spaces.

Every pinned repository should have:

- A precise one-line description
- A clean README with a screenshot or terminal demo
- Installation and usage instructions
- A responsible-use statement where relevant
- Relevant topics such as `cybersecurity`, `threat-hunting`, `soc`, `python`, `nmap`, or `security-automation`
- A license when the code is intended for reuse
- No credentials, internal logs, client names, private IPs, or confidential SOC screenshots

## 6. Recommended repository names

Use clear names that a recruiter or security engineer can understand immediately:

```text
zephryx
web-enumeration-playbook
soc-automation-lab
dga-analysis-toolkit
linux-100
cybersecurity-cheatsheets
```

Suggested descriptions:

- `zephryx` — Terminal-first cybersecurity platform for practical labs, research, and education.
- `web-enumeration-playbook` — Repeatable web-service enumeration workflows for authorized labs and CTFs.
- `soc-automation-lab` — Python utilities for analyst reporting, data processing, and repetitive SOC workflows.
- `dga-analysis-toolkit` — Heuristics and utilities for investigating suspicious and algorithmically generated domains.
- `linux-100` — Practical Linux exercises designed for cybersecurity learners.
- `cybersecurity-cheatsheets` — Concise command references with practical examples and responsible-use notes.

## 7. Profile design rules

Keep the profile premium and credible:

- One branded animated banner
- One clear professional statement
- Visible proof of work
- Minimal effects
- No visitor counter
- No ten-card wall of statistics
- No unsupported skill claims
- No excessive emojis
- No fake “hacker” language
- No confidential work data

The profile should communicate: **operator, builder, educator**.
