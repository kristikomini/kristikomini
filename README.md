### Kristi Komini

Backend developer, based in Modena. Studying computer science at the University of Camerino.

Most of what I build is server-side: .NET and Java/Spring on the backend, with whatever
frontend the job needs (TypeScript, PHP, a bit of Vue). Lately I've been working through
the problems that actual companies around Emilia-Romagna have — legacy modernization,
e-invoicing, order and warehouse systems, factory-floor telemetry — because that's the
work that's here and it's more interesting than another to-do app.

I learn a pattern by building something real with it. A few I'd point at:

- **[industrial-telemetry-streaming](https://github.com/kristikomini/industrial-telemetry-streaming)** — 120 simulated machines streaming into Kafka, a stateful processor watching for overheats, a .NET service pushing alerts to a live dashboard. Engine dynos and packaging lines, the machinery this region actually builds.
- **[logiflow-lab](https://github.com/kristikomini/logiflow-lab)** — a warehouse platform in .NET 10 done the long way: Clean Architecture, a hand-rolled CQRS dispatcher, EF Core, tests. Comes with a course I wrote against the codebase.
- **[orders-events](https://github.com/kristikomini/orders-events)** — event-driven order/inventory/shipment services over Kafka: transactional outbox, idempotent consumers, a saga with compensation, and a concurrency shootout to see what actually prevents overselling.
- **[fatturazione-sdi](https://github.com/kristikomini/fatturazione-sdi)** — Italian e-invoicing: FatturaPA XML, the SDI state machine, and gap-less invoice numbering that survives concurrent requests. Boring on paper, genuinely fiddly in practice.
- **[Java_Spring_Boot_Tutorial](https://github.com/kristikomini/Java_Spring_Boot_Tutorial)** — a Spring Boot course-enrollment app where I commented every class with what it does and why, mostly so I'd actually understand it.

Still a student, so the repos are where I think out loud. If something looks half-finished
it probably is.

Reachable at kristi.komini@studenti.unicam.it.
