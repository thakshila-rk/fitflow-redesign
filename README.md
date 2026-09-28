# FitFlow redesign - IT3060 Lab Exercise 05

Technology selection and high-level architecture documentation for a fitness app across iOS, Android and web. This is a lab scaffold, not a functional application.

## Contents
- `docs/Lab_Report.md` - complete Activities 1-5, tables and submission checklist
- `docs/architecture.mmd` - editable Mermaid architecture diagram
- `docs/decision-matrix.csv` - weighted comparison, scores 1-5
- `docs/ADR-001.md` - architectural decision record
- `frontend/`, `backend/`, `ai-service/` - reserved implementation directories

## Publish the first commit
1. On GitHub, create an empty repository named `fitflow-redesign`. Do not initialize it with a README.
2. From this folder, run:

```bash
git init -b main
git add .
git commit -m "Add FitFlow lab architecture and technology comparison"
git remote add origin https://github.com/YOUR_USERNAME/fitflow-redesign.git
git push -u origin main
```

3. Replace `thakshila-rk` in the URL and the report. Configure repository Settings > Rules > Rulesets (or branch protection) for `main` as appropriate; require a pull request and checks once checks are configured.
4. Check the CourseWeb case study for requirements absent from the lab sheet before submission.

## Proposed stack
Flutter clients; NestJS API and WebSocket gateway; FastAPI AI service; PostgreSQL; Supabase Auth; Redis. See `docs/Lab_Report.md` for assumptions, alternatives, privacy and reasoning.
