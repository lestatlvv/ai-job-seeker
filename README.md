# ai-job-seeker
This repo is a modular Node.js + TypeScript job-seeking pipeline. Services stay independent (subprocess adapters, not a monolith) and can run standalone or through an orchestrator.  Pipeline: listing URLs + CV → optional CV classification → scrape → optional salary estimation → match CV to vacancies → HTML/Telegram report.
