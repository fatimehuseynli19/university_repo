# TASKS.md — Kanban Task Cards

Create each task below as a **GitHub Issue** and add it to your Kanban board under **Backlog**.
Assign each issue to a team member before you start the sprint.

---

## How to create an Issue

1. Go to the repository on GitHub.
2. Click the **Issues** tab.
3. Click **New issue**.
4. Copy the task title exactly as written below.
5. Paste the task description into the body.
6. Assign it to a team member.
7. Click **Submit new issue**.
8. Open your Kanban board and add the issue as a card under **Backlog**.

---

## Tasks

---

### `chore: fork the repo and configure remotes`

**Assigned to:** *(pick one person or all)*

1. Fork the repository to your personal GitHub account.
2. Clone your fork locally.
3. Add the original repo as `upstream`.
4. Run `git remote -v` and confirm both `origin` and `upstream` appear.
5. Post a screenshot of your terminal output in the Issue comments as proof.

---

### `chore: add all teammates as collaborators`

**Assigned to:** *(repo owner)*

1. Go to Settings → Collaborators.
2. Add every teammate by GitHub username.
3. Confirm all teammates have accepted their invitation.
4. Leave a comment on this Issue once everyone has access.

---

### `chore: set up the Kanban board`

**Assigned to:** *(repo owner or any one person)*

1. Create a Board-type project named `Sprint 1`.
2. Add the columns: `Backlog`, `To Do`, `In Progress`, `In Review`, `Done`.
3. Create a GitHub Issue for every task in this file.
4. Add all issues as cards under **Backlog**.
5. Assign each card to a teammate.

---

### `feat: create your first feature branch`

**Assigned to:** *(each student individually)*

1. Pull the latest `main`.
2. Create a branch named `feat/YOUR_NAME-first-branch`.
3. Create a file at `bios/YOUR_NAME.md`.
4. Write 3–5 sentences about yourself inside it.
5. Commit with the message `docs(bios): add YOUR_NAME bio`.
6. Push the branch.
7. Open a Pull Request using the PR template in `CONVENTIONS.md`.

---

### `feat: review and merge a teammate's PR`

**Assigned to:** *(each student reviews someone else's PR)*

1. Open a teammate's Pull Request.
2. Read through the changes in the **Files changed** tab.
3. Leave at least one comment or suggestion.
4. If everything looks good, click **Approve**.
5. Click **Merge pull request**.
6. Move the teammate's Kanban card to **Done**.

---

### `chore: sync your branch after a teammate merges`

**Assigned to:** *(everyone)*

1. Wait until at least one teammate's PR has been merged into `main`.
2. Run the daily sync commands from `CONVENTIONS.md` Part 6.
3. Confirm your branch is up to date with `git log --oneline -5`.
4. Post the output in the Issue comments.

---

### `feat: simulate and resolve a merge conflict`

**Assigned to:** *(two students working together)*

1. Both students create a branch from `main`.
2. Both students edit the **same line** in `bios/shared.md` (create this file if it doesn't exist).
3. Both students commit and push their branches.
4. One student opens a PR and merges it first.
5. The second student syncs their branch using rebase.
6. The second student resolves the conflict manually.
7. The second student pushes and opens their PR.
8. Take a screenshot of the resolved conflict and post it in the Issue comments.

---

### `docs: update README with what you learned`

**Assigned to:** *(each student individually)*

1. Create a branch named `docs/YOUR_NAME-reflection`.
2. Open `README.md`.
3. Add a `## What I learned` section at the bottom.
4. Write at least 3 things you learned during this project.
5. Commit with `docs: add YOUR_NAME reflection to README`.
6. Push and open a PR.
7. Assign a teammate as reviewer.
