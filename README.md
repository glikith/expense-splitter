# Expense Splitter

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?style=for-the-badge&logo=chartdotjs&logoColor=white)
![Vanilla JS](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

> A zero-setup group expense tracker for travel trips — split bills, track balances, and visualize spending, all in a single HTML file.

---

## Overview

Expense Splitter is a client-side web app for managing shared trip finances. Add members, log expenses, choose a split method (equal, exact, or percentage), and instantly see who owes what. All data lives in-memory — no backend, no build step, no installs. Open the file and it works.

---

## Features

| Feature | Description |
|---|---|
| Trip Management | Create and delete trips; each trip has its own members, budget, and expense list |
| Expense Logging | Add expenses with description, amount, payer, category, and split method |
| Split Methods | Split equally, by exact amount, or by percentage |
| Balance Calculation | Per-member interpersonal balances — see exactly who owes whom |
| Expense Detail Modal | View settlement status (paid / owes) per member for each expense |
| Analytics Tab | Category breakdown (doughnut), contributions per person (pie) |
| My Spending Tab | Personal budget tracker with a doughnut gauge and category bar chart |
| Expense Calendar | Monthly calendar view showing which days had recorded expenses |
| Dark Mode | Full dark/light theme toggle, persisted via localStorage |
| Invite Link | Copy-to-clipboard trip invite link |

---

## Tech Stack

```
Markup         : HTML5
Styling        : Tailwind CSS (CDN)
Charts         : Chart.js (CDN)
Logic          : Vanilla JavaScript (no frameworks)
Fonts          : Inter via Google Fonts
Data Storage   : In-memory (mock data, no backend)
```

---

## Author

[Gummadi Likith](https://github.com/glikith)
