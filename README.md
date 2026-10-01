# Hey, I'm Vinícius 👋

Full-stack developer from Bento Gonçalves, Brazil. Most of my work is React/TypeScript on the front, Node.js (NestJS) on the back, AWS underneath. These days a lot of it involves getting LLMs to do useful work in production, which turns out to be mostly about evals, cost tracking and knowing when the model should say "I don't know".

At Taxly I built the pipeline that reads tax documents with OCR and an LLM (353 documents in about 3 minutes, instead of hours of manual entry), owned the analytics module from zero to production (95 endpoints) and cut perceived load time by about 80%.

My day-to-day work lives in private repositories under [@vinicmorandi-taxly](https://github.com/vinicmorandi-taxly) — 1,200+ contributions in the last year.

## Side projects

**[grifo](https://github.com/vinicmorandi/grifo)** answers questions about Brazilian tax law and points to the exact passage behind every claim. A second model checks the answer, and when something can't be backed up, grifo refuses instead of guessing. It passes all 13 eval cases on two different model families.

**[docpipe](https://github.com/vinicmorandi/docpipe)** takes a PDF or an image, works out what kind of document it is and pulls structured data out of it. Anything below a confidence threshold goes to a human for review. It gets every field right on its golden set, and the E2E tests run in CI on every push.

**[wooper](https://github.com/vinicmorandi/wooper)** is a real-time 1v1 battle simulator. The server validates every move, 135 tests try to cheat it, and the whole thing runs on AWS ECS Fargate for about $22 a month. [Try it here](https://wooper-demo.vercel.app).

## Stack

**Daily:** TypeScript, React, Vue/Nuxt, NestJS, PostgreSQL, Prisma, Docker, AWS

**Often:** Python, Laravel, Next.js, RabbitMQ, OpenAI APIs, Jest/Vitest

**Now and then:** Go, Angular, Deno, MongoDB

## Find me

[Portfolio](https://vinicmorandi.com/) · [LinkedIn](https://www.linkedin.com/in/vinicmorandi/) · [Email](mailto:viniciuscmorandi@gmail.com)
