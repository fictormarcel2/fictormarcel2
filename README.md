## Hi, I'm Fictor ✨

Computer science student at **FH Aachen** building full-stack products, AI tooling for coding agents, and the occasional neural network from scratch.

* 🚀 Currently building **Aure Social Indonesia**: a marketing site, client portal and KOL platform for a social media agency
* 🧹 Maintaining **[untangle-everything](https://github.com/fictormarcel2/untangle-everything)**, an agent skill that cleans up AI-generated codebases
* 🌍 Shipping **[Little Trips](https://github.com/fictormarcel2/little-trips)**, a shared 3D travel journal

---

## 💻 Tech Stack

### 🚀 Languages
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E) ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![PHP](https://img.shields.io/badge/php-%23777BB4.svg?style=for-the-badge&logo=php&logoColor=white) ![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white) ![C](https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white) ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)

### 🧩 Frameworks & Libraries
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB) ![Next JS](https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white) ![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white) ![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB) ![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white) ![Three.js](https://img.shields.io/badge/threejs-black?style=for-the-badge&logo=three.js&logoColor=white) ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)

### 🗄️ Databases & Backend
![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white) ![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white) ![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&logo=mariadb&logoColor=white) ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)

### 🛠️ Tools
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white) ![GitLab](https://img.shields.io/badge/gitlab-%23181717.svg?style=for-the-badge&logo=gitlab&logoColor=white) ![Claude](https://img.shields.io/badge/Claude%20Code-D97757?style=for-the-badge&logo=claude&logoColor=white) ![LaTeX](https://img.shields.io/badge/latex-%23008080.svg?style=for-the-badge&logo=latex&logoColor=white)

---

## 🌟 Featured Projects

### 🧹 [Untangle Everything](https://github.com/fictormarcel2/untangle-everything)
*An agent skill for Claude Code, Cursor and Codex that audits and refactors AI-generated codebases, with a human approving every decision.*
* **Audit:** read-only pass that runs the build and tests, finds 13 kinds of tangle (duplicate files, dead code, competing patterns), deliberately breaks business rules to see whether the tests notice, and scores a 14-point scorecard.
* **Triage → Refactor:** ranks findings by risk, then works through approved fixes in small, tested, separately committed slices on a branch.
* **Sustain:** turns each decision into lint rules, CI checks, `AGENTS.md` and ADRs so coding agents stop recreating the mess.
* Install: `npx skills add fictormarcel2/untangle-everything`

### 🌍 [Little Trips](https://github.com/fictormarcel2/little-trips)
*A shared travel journal for couples and small groups. Collect ideas, vote together and plan your days.*
* **Stack:** Next.js, React, TypeScript, Supabase (Postgres, realtime), Tailwind, React Three Fiber.
* **Features:** photographic idea postcards, per-account reversible votes, multi-day drag-and-drop planning, and an interactive Three.js Journey kept in sync with a Google Map.
* **Polish:** magic-link and guest invites, light/dark themes, adjustable effect levels with reduced-motion fallbacks, and CI-verified QA.

### 🍽️ [MensaTogether (EMensa)](https://github.com/fictormarcel2/EMensa)
*A responsive lunch coordination app for FH Aachen: compare lunch times, pick one arrival slot and share the plan with friends.*
* **Stack:** TypeScript web client, PHP API, MariaDB and a reminder worker, all running in Docker Compose.
* **Rules enforced server-side:** one confirmed slot per user per day, only future slots inside published service hours, and plans private by default.

### 🏢 Aure Social Indonesia *(private)*
*A production platform for a social media agency: public marketing site, multi-role client portal, and a separate KOL platform.*
* **Stack:** pnpm monorepo, React + Vite, Express 5, PostgreSQL + Drizzle, Clerk auth, OpenAPI-generated Zod types.
* **Portal:** approval centre, content plan calendar, AI brief assistant (editable drafts a human approves), feed preview grid and tracking, with access rules covered by integration tests.

---

## 🤖 AI & Machine Learning

### 🧠 [Neural Network Digit Classifier](https://github.com/fictormarcel2/neural-network-digit-classifier)
*A feedforward neural network written in plain Python and NumPy, with no ML frameworks, that classifies MNIST handwritten digits.*
* **Architecture:** 784 × 200 × 10 network mapping grayscale pixel inputs to digit outputs.
* **Core mechanics:** vectorized forward propagation and backpropagation, sigmoid activations, and gradient-descent updates of the weight matrices (W_ih, W_ho) from the output error (E_out = T − O).

### 🕹️ Pacman AI Series
*Three repositories built on the UC Berkeley Pacman framework, all passing the automated autograder.*
* **[Pacman Search](https://github.com/fictormarcel2/Pacman-Search):** uninformed and informed search (DFS, BFS, UCS, A*) for navigation and pathfinding puzzles.
* **[Pacman Multiagents](https://github.com/fictormarcel2/Pacman-Multiagents):** adversarial search with minimax, alpha-beta pruning, expectimax and custom evaluation functions.
* **[Pacman Reinforcement Learning](https://github.com/fictormarcel2/Pacman-Reinforcement-Learning):** Q-learning agents with feature extractors that learn optimal policies from rewards.

---

## 🔭 Other Engineering Work
* **[Lernhub](https://github.com/fictormarcel2/Lernhub):** a PHP and MariaDB e-learning platform with session management, database views and secure password hashing.
* **Model-Based Systems Engineering:** ADAS architectures using Fault Tree Analysis (FTA), DFMEA risk optimization and automated Mermaid.js documentation, compliant with ISO 26262.

---

## 🌐 Socials
[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/FictorMarcelbrian) [![Email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:fictormarcel1@gmail.com) [![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?logo=Instagram&logoColor=white)](https://instagram.com/fictormarcel)
