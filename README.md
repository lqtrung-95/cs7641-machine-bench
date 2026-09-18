# Machine Bench — CS 7641 review site

A single-page, self-contained review site for Georgia Tech OMSCS **CS 7641: Machine Learning**
(Isbell & Littman). No build step, no dependencies, no tracking — one HTML file.

**Live:** _add your Netlify / Vercel URL here_

## What's inside

- **32 topics across 5 units** — Foundations (inductive bias, bias–variance, information theory,
  evaluation), Supervised Learning (decision trees/ID3, k-NN, neural nets & backprop, SVMs & kernels,
  bagging vs boosting, PAC & VC theory, Bayesian learning), Randomized Optimization (RHC, simulated
  annealing, genetic algorithms, MIMIC, benchmark problems), Unsupervised Learning & Dimensionality
  Reduction (k-means, EM/GMM, linkage & Kleinberg's impossibility theorem, filtering vs wrapping,
  PCA/ICA/RCA/LDA), and Reinforcement Learning (MDPs, Bellman equations, value & policy iteration,
  Q-learning vs SARSA, exploration strategies, POMDPs, game theory).
- **6 interactive canvas demos** — binary entropy & information gain, k-NN decision boundary,
  polynomial bias–variance fit, simulated annealing on a rugged landscape, Lloyd's algorithm
  step-by-step, and value iteration on a stochastic gridworld with the greedy policy drawn.
- **67 flashcards** in five decks, 10 self-test questions, and a night-before cheatsheet
  (formula table, "which algorithm when", common traps, Mitchell chapter map).
- **Week-by-week schedule** synced to the Fall 2026 syllabus — a "this week" banner plus a full
  16-week table (lessons, due dates), auto-highlighted from the browser's clock. Lessons with no
  matching topic on the site yet are marked "not here yet" instead of link. Edit the `SCHED` array
  in the script if your section's dates differ.
- **ELI5 + Vietnamese explanations** — every concept topic has a collapsible "Explain like I'm 5" box and a
  plain-language Vietnamese explanation (key English terms kept in parentheses to match the exam).
- **Mock final exam** — 121 multiple-choice / multi-select / true-false questions across SL, RO, UL and RL,
  with per-question feedback and a running score.
- Full-text search, per-topic progress tracking (`localStorage`), light/dark/system themes.

## Running it

Open `index.html` in a browser. That's the whole thing.

## Deploying

**Netlify** — drag the folder onto app.netlify.com, or connect the repo (build command: none,
publish directory: `.`).

**Vercel** — `vercel` from this folder, or import the repo; framework preset "Other",
output directory `.`.

**GitHub Pages** — Settings → Pages → Deploy from branch → `main` / root.

## Notes

Study notes only. No assignment code, solutions, or report content — please keep it that way if
you fork it, per the Georgia Tech Academic Honor Code.
