<div align="center">

# Muhammad Faizan Sajid

**DevOps Portfolio · CI/CD · Containers · Deployment Automation**

Computer Science graduate in Peshawar, Pakistan · Open to junior DevOps roles

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/faizan102418/)
[![Email](https://img.shields.io/badge/Email-Get_in_touch-334155?style=flat-square)](mailto:m.faizansajid102418@gmail.com)

</div>

I bring a Python backend background to DevOps. I’m focused on automating the steps between a code change and a verified deployment, including testing, container builds, health checks, and database recovery.

## Featured project · HighFly Hospitality

A hotel management application with a FastAPI backend, React frontend, and PostgreSQL. The repository shows how application changes are tested and how deployments are checked.

| Area | Repository evidence |
| --- | --- |
| **Continuous integration** | GitHub Actions runs API tests, applies PostgreSQL migrations, checks that migrations can be rerun, and builds the frontend. [CI workflow](https://github.com/faizan102418/highfly-hospitality/blob/main/.github/workflows/ci.yml) |
| **Deployment** | Render configuration defines separate development and staging services and databases. [Deployment configuration](https://github.com/faizan102418/highfly-hospitality/blob/main/render.yaml) |
| **Readiness and recovery** | A scheduled workflow checks the service readiness endpoint, and CI exercises a PostgreSQL backup-and-restore round trip. [Readiness workflow](https://github.com/faizan102418/highfly-hospitality/blob/main/.github/workflows/production-readiness-smoke.yml) · [Recovery runbook](https://github.com/faizan102418/highfly-hospitality/blob/main/docs/operations/offline-deployment-and-recovery.md) |

[Explore HighFly Hospitality →](https://github.com/faizan102418/highfly-hospitality)

## More project work

- **[Centralized Student Information System](https://github.com/faizan102418/Centralized-Student-Information-system)** — Docker Compose runs the FastAPI service and MySQL with persistent volumes and health-based startup ordering.
- **[FlyRank AI Internship](https://github.com/faizan102418/FlyRank-AI-Internship/tree/main/CRUD)** — A containerized FastAPI CRUD service with PostgreSQL and a locked Python dependency set.

## Toolkit

**Used in projects** · Git · GitHub Actions · Docker · Docker Compose · Python · PostgreSQL · MySQL · Render

**Currently practicing** · Linux administration · Bash · SSH · Networking · AWS fundamentals

**Next lab** · Use the [Finance Tracker API](https://github.com/faizan102418/finance-tracker-api) to practice publishing a versioned Docker image, deploying it to a Terraform-managed Linux VM, and verifying a rollback in a local Kubernetes cluster.
