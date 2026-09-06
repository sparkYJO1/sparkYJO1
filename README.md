### John Yoon

Backend engineer near Seoul. I write the services and run the Kubernetes they
live on — four applications plus the Redpanda, Redis, database and cron
workloads behind them, with a five-person team and no dedicated infrastructure
engineer.

The work I like most is the part nobody sees: pulling hard-coded domain logic
out into data-driven rule systems, so changing a rule stops needing a deploy —
and stops needing an engineer.

I build with AI agents daily and 0→1: project inception, CI/CD and deployment,
not autocomplete. Where that shows up in a repo here, the decision documents
record what an agent proposed and I rejected, because supervising one and
following one are different jobs.

**Stack** — TypeScript · NestJS · Node.js · PostgreSQL · Redis · Kafka
(Redpanda) · Docker · Kubernetes · AWS

---

**[signalpipe](https://github.com/sparkYJO1/signalpipe)** — an ingest pipeline
built around a slow, expensive, non-deterministic consumer. Idempotency keyed on
content rather than id, backpressure left readable as consumer lag, retries that
cannot stall a partition. Runs on `docker compose up` with no API key.

---

BSc Computer Science, taught in English, University of Pretoria.
[sparkj.yoon@gmail.com](mailto:sparkj.yoon@gmail.com) ·
[LinkedIn](https://www.linkedin.com/in/jyoon93)
