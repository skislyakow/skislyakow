<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=28&duration=2500&pause=1000&color=58A6FF&center=true&vCenter=true&width=700&lines=Python+Backend+%2F+Full-Stack+Developer;Django+%7C+DRF+%7C+FastAPI+%7C+PostgreSQL+%7C+Redis;Telegram+%26+VK+Bots+%7C+aiogram+%7C+CI%2FCD" />
    <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=28&duration=2500&pause=1000&color=0969DA&center=true&vCenter=true&width=700&lines=Python+Backend+%2F+Full-Stack+Developer;Django+%7C+DRF+%7C+FastAPI+%7C+PostgreSQL+%7C+Redis;Telegram+%26+VK+Bots+%7C+aiogram+%7C+CI%2FCD" alt="Python Backend / Full-Stack Developer" />
  </picture>

  <h2>Python Backend / Full-Stack Developer</h2>

  <a href="https://kislyakov.pro/"><img src="https://img.shields.io/badge/Portfolio-kislyakov.pro-1F6FEB?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio" /></a>
  <a href="https://t.me/kislyakow"><img src="https://img.shields.io/badge/Telegram-%40kislyakow-2AABEE?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram" /></a>
  <a href="https://vk.com/skislyakov84"><img src="https://img.shields.io/badge/VK-skislyakov84-0077FF?style=for-the-badge&logo=vk&logoColor=white" alt="VK" /></a>
  <a href="mailto:s.kislyakov84@gmail.com"><img src="https://img.shields.io/badge/Email-s.kislyakov84%40gmail.com-6F42C1?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</div>

---

## About Me

- 👋 I design and ship Python web services and bots — from data model and API to CI/CD and production deployment.
- 🔭 Currently working at **EFKO**.
- 📍 Based in **Ostrogozhsk, Russia** — open to remote.
- 💼 **Open to work / collaboration** — the fastest way to reach me is [Telegram](https://t.me/kislyakow).

---

## Tech Stack

**Core** — the tools I'm ready to discuss in depth at a technical interview:

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![DRF](https://img.shields.io/badge/DRF-A30000?style=for-the-badge&logo=django&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![aiogram](https://img.shields.io/badge/aiogram-2AABEE?style=for-the-badge&logo=telegram&logoColor=white)

</div>

**Also used** in day-to-day work and projects:

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=python&logoColor=white)
![Alembic](https://img.shields.io/badge/Alembic-009688?style=flat-square&logo=alembic&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
![mypy](https://img.shields.io/badge/mypy-2A6DB2?style=flat-square&logo=python&logoColor=white)
![Ruff](https://img.shields.io/badge/Ruff-D7FF64?style=flat-square&logo=ruff&logoColor=black)

---

## Selected Projects

The two flagship projects are broken down below; here are the rest.

| Project | Description | Stack |
|---|---|---|
| [dossier](https://github.com/skislyakow/dossier) | Portfolio site with auto-generated PDF résumé and CI/CD deploy · [live](https://kislyakov.pro) | Django, WeasyPrint, Nginx, GitHub Actions |
| [BeautyCity](https://github.com/skislyakow/BeautyCity) | Beauty-salon booking: server-side slot calculation, SMS login, YooKassa, staff stats · [demo](https://beauty.kislyakov.pro) | Django, DRF, YooKassa |
| [star-burger](https://github.com/skislyakow/star-burger) | Food-delivery storefront: React cart, manager dashboard, geocoding · [demo](https://star-burger.kislyakov.pro) | Django, DRF, React, PostgreSQL, CI |
| [FishShop](https://github.com/skislyakow/FishShop) | Telegram seafood shop backed by a headless Strapi CMS, Redis FSM | python-telegram-bot, Strapi, Redis |
| [opencode-py](https://github.com/skislyakow/opencode-py) | Python SDK for the Opencode AI coding agent (typed, streaming, async) | Pydantic, httpx |

Also: **fastai-api** (AI site generator REST API), **ferma** (Telegram/VK channel automation), **support-bot** (Dialogflow support bot), **Devman-monitor** (systemd watchdog) — see [all repositories](https://github.com/skislyakow?tab=repositories).

---

## ⭐ Featured Projects

### 🗄️ SelfStorage — storage rental with online payments
> Django service: pick a warehouse and a box, pay online, get a QR code for the door.

- 🧭 **Multi-step checkout** — `SessionWizardView` with server-side validation on every step, promo codes with date windows and per-month price calculation.
- 💳 **Payments without duplicates** — one `Payment` per order via `get_or_create`; the webhook and the `return_url` both go through one idempotent `_mark_paid` guarded by status checks, so a repeated webhook never re-sends emails or regenerates the QR.
- 🔒 **No double booking** — the box is re-checked as `free` on every step and set to `reserved` when the order is created.
- 🔑 **Access & lifecycle** — QR door codes, in-app notification feed, reminder emails (30/14/7/3 days before the end, plus overdue).
- 📊 **Owner dashboard** — occupancy, orders and revenue; CI gate with ruff + mypy.

🔗 [github.com/skislyakow/SelfStorage](https://github.com/skislyakow/SelfStorage) · [live demo](https://selfstorage.kislyakov.pro)

### 🧠 quiz-bot — multi-platform quiz bot
> Quiz bot for Telegram & VK on a base of ~300k questions.

- 🤖 **Two platforms, one logic** — Telegram (aiogram) + VK (vkbottle) as independent processes sharing common modules.
- ⚡ **Fast startup** — ~302k-question cache with fingerprint-based auto-invalidation; O(1) random pick.
- 🧠 **Smart answer matching** — pymorphy3 lemmatization, punctuation normalization, partial-match tolerance.
- 🗄️ **Resilient state** — FSM in Redis with TTL; graceful degradation if Redis is down.

🔗 [github.com/skislyakow/quiz-bot](https://github.com/skislyakow/quiz-bot)

---

## 📜 Certifications

<table>
  <tr>
    <td width="45%" align="center">
      <a href="https://stepik.org/cert/3370001">
        <img src="assets/certificates/stepik-interactive-sql-trainer.png" width="360" alt="Stepik certificate — Интерактивный тренажер по SQL, с отличием" />
      </a>
    </td>
    <td>
      <b>Интерактивный тренажер по SQL</b> — <i>с отличием</i><br/>
      <sub>Stepik · hands-on SQL practice: SELECT, JOINs, subqueries, aggregation</sub>
      <br/><br/>
      <a href="https://stepik.org/cert/3370001">Verify on Stepik</a> · <a href="https://stepik.org/course/63054">Course page</a>
    </td>
  </tr>
</table>

---

## 📊 GitHub at a glance

<div align="center">
  <img src="https://img.shields.io/github/stars/skislyakow?style=for-the-badge&label=Stars&color=1F6FEB" />
  <img src="https://img.shields.io/github/followers/skislyakow?style=for-the-badge&label=Followers&color=1F6FEB" />
  <img src="https://img.shields.io/badge/dynamic/json?style=for-the-badge&label=Repos&color=1F6FEB&query=%24.public_repos&url=https%3A%2F%2Fapi.github.com%2Fusers%2Fskislyakow" />
  <img src="https://img.shields.io/github/last-commit/skislyakow/skislyakow?style=for-the-badge&label=Updated&color=1F6FEB" />
  <img src="https://komarev.com/ghpvc/?username=skislyakow&color=1F6FEB&style=for-the-badge&label=Profile+Views" />
</div>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/skislyakow/skislyakow/output/github-contribution-grid-snake-dark.svg" />
    <img src="https://raw.githubusercontent.com/skislyakow/skislyakow/output/github-contribution-grid-snake.svg" alt="GitHub contribution snake" />
  </picture>
</p>
