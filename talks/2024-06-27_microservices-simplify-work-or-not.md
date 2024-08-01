# Microservices (don't) simplify work

## Details

- Date: 2024-06-27
- Platform: https://hardsoftskills.dev/calendar

## Talk - pros and cons of microservices

### Comments from users:
- How to organize git repositories?
- Harder monitoring
- Company needs to be mature for microservices (DevOps, organizational)
- Why are microservices trending?
- Easier to release changes (no need to redeploy the whole app)
- Different services can have different SLAs (load / latency requirements)

### Why they are trending
- Microservices are suitable for complex applications
- The number of high-load projects has increased
- Side note: Stackoverflow has a monolith architecture 😮

### Monolith vs microservice and other ideas

Someone's opinion: startups can start as monoliths

Microservices solve some problems, but bring new ones 😄

[Conway's law](https://en.wikipedia.org/wiki/Conway%27s_law)

Saga pattern

Shared database between microservices: who owns it?

**Ideal** microservices: isolated; persistence is also isolated

Documentation required on how the system works for newcomers (compared to easier onboarding to a monolith project)

Database triggers / procedures: good or bad? Seems to hard to maintain / migrate

Distributed transactions / data consistency

CAP theorem

Google Spanner - the system, that "beat" the CAP theorem (advanced hardware)

Code of conduct

Fitness function

Pods in microservices

Locking in microservices

Harder debugging