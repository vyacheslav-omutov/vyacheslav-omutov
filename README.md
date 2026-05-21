# Hi, I'm Vyacheslav Omutov 👋

**Full-Stack .NET / Angular Developer** focused on enterprise web systems, cloud integrations, email workflows, indexing/search, and desktop sync applications.

I work across backend, frontend, and Windows desktop applications — from API design and data access to Angular UI, SignalR-based flows, background indexing, cloud storage integrations, and access-control logic.

---

## What I work with

### Backend
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET_Core-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![EF Core](https://img.shields.io/badge/EF_Core-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![ABP Framework](https://img.shields.io/badge/ABP_Framework-3D5AFE?style=for-the-badge)
![REST API](https://img.shields.io/badge/REST_API-02569B?style=for-the-badge)
![gRPC](https://img.shields.io/badge/gRPC-244C5A?style=for-the-badge)

### Frontend
![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![RxJS](https://img.shields.io/badge/RxJS-B7178C?style=for-the-badge&logo=reactivex&logoColor=white)
![PrimeNG](https://img.shields.io/badge/PrimeNG-1E88E5?style=for-the-badge)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

### Desktop / Infrastructure
![Avalonia UI](https://img.shields.io/badge/Avalonia_UI-6A5ACD?style=for-the-badge)
![WPF](https://img.shields.io/badge/WPF-512BD4?style=for-the-badge)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

---

## Engineering focus

- Building **enterprise .NET / Angular applications** with clean boundaries between backend, UI, desktop client, and infrastructure.
- Designing and implementing **cloud storage integrations** for Autodesk, SharePoint, Egnyte, and Google-related workflows.
- Working on **folder and email indexing**, search flows, pagination, sorting, filtering, and Lucene-based indexing scenarios.
- Implementing **email workflows**: opening messages in Outlook, filing emails, downloading/printing messages, handling attachments, and processing `.msg` files.
- Building **access-control and permissions logic** for public/shared storages, ACL validation, actor-token usage, and visibility rules.
- Developing **webhook-based synchronization** and notification flows for cloud storage changes.
- Supporting **desktop sync applications** with Avalonia UI, background processing, and backend API communication.
- Improving performance by reducing external API calls during indexing and synchronization.

---

## Selected work highlights

### Cloud storage indexing and search

I worked on indexing folders and emails from multiple cloud storage providers, including Autodesk, SharePoint, and Egnyte.  
This included folder indexing, message indexing, pagination, faster re-indexing, path handling, webhook-driven updates, and Lucene interaction refactoring.

Key areas:

- folder and message indexing;
- search preview and filtering improvements;
- sorting support for search columns;
- avoiding unnecessary re-indexing of already indexed files;
- reducing external API calls during indexing;
- folder index diagnostics and visibility in sync tooling.

### Webhooks and background synchronization

I implemented and improved webhook-related flows for cloud storages, especially Autodesk-related scenarios.

Key areas:

- tracking folder changes through webhooks;
- subscribing and unsubscribing from webhook events;
- handling deleted or moved parent folders;
- updating folder/file index paths after webhook notifications;
- disabling stale webhooks when sync is not active.

### Access control for shared locations

I worked on flexible access management for shared cloud locations and public storages.

Key areas:

- Windows ACL support for storages;
- shared storage visibility rules;
- permissions validation during indexing;
- preventing access to restricted locations;
- actor-token based upload behavior;
- company-level shared storage scenarios.

### Outlook and email workflows

I worked on email-specific UX and backend flows around search, filing, attachments, and Outlook integration.

Key areas:

- reply, forward, open, print, and download actions from search results;
- opening messages in the Outlook desktop application;
- saving attachments separately;
- attachment support for cloud storages;
- `.msg` attachment processing;
- filing history and notification-related flows.

### Frontend and desktop UI

I maintain and improve multiple client applications: manager frontend, plugin frontend, and Avalonia-based desktop sync UI.

Key areas:

- Angular UI refactoring and localization;
- search view improvements;
- preview UX improvements;
- dark mode and layout fixes;
- Avalonia desktop sync screens;
- desktop diagnostics for indexing and folder state.

---

## Current direction

I'm currently focused on improving production-level engineering skills around:

- scalable backend architecture with .NET, ABP Framework, EF Core, and background processing;
- robust Angular applications with modern TypeScript, Signals, RxJS, and feature-based architecture;
- cloud storage integrations and synchronization reliability;
- indexing/search performance;
- secure access-control models;
- observability, diagnostics, and production maintainability.

---

## Contacts

- Telegram: [@vyacheslav_omutov](https://t.me/vyacheslav_omutov)
- Habr Career: [career.habr.com/vyacheslav-omutov](https://career.habr.com/vyacheslav-omutov)
- Email: [vyacheslav.omutov@mail.ru](mailto:vyacheslav.omutov@mail.ru)

---

## GitHub stats

<p align="center">
  <a href="https://github.com/vyacheslav-omutov">
    <img
      height="180em"
      src="https://github-readme-stats-eight-theta.vercel.app/api?username=vyacheslav-omutov&show_icons=true&theme=radical&count_private=true"
      alt="Vyacheslav's GitHub stats"
    />
  </a>
</p>

---

## Profile summary

I prefer practical engineering over abstract complexity: clear architecture, reliable data flows, predictable behavior under load, and maintainable code that can evolve with the product.
