# Hi, I'm Venkatesh 👋

I'm a Software Engineer based in Pune, India. I currently own a 19-microservice .NET + Azure platform serving U.S. enterprise clients at [Agnotic Technologies](https://agnotic.com).

## What I'm working on

- **Distributed systems on Azure** — designing and shipping production microservices on .NET Core, Azure Service Bus, and Azure Function Apps.
- **Payment & queue pipelines** — multi-stage Service Bus pipelines for GiftCard and PayPal payouts at scale (tens of thousands/day).
- **Performance work on SQL Server** — schema, index, and query tuning on tables with 3.5M+ rows using Dapper.
- **Distributed debugging** — finding silent failures across 19 services using Azure Application Insights and KQL.

## Tech I work with daily

**Languages:** C#, TypeScript, JavaScript, SQL, Python
**Frameworks:** .NET Core, ASP.NET Core, Angular, React, Node.js, Spring Boot
**Cloud:** Azure (Service Bus, Functions, App Service, App Insights), AWS (Lambda)
**Data:** SQL Server, PostgreSQL, MongoDB, Redis, Dapper
**DevOps:** Azure DevOps, GitHub Actions, CI/CD pipelines, Locust load testing

## A few things I've shipped

- A **Bulk-Requeue System** that reduced failed-incentive recovery from days of manual Postman work to a few admin clicks across 19 microservices. Built with parallel async processing in C# and a clean state-machine for audit-clean retries.
- **Production payout pipelines** for GiftCard and PayPal on Azure Service Bus — multi-stage validation → fraud check → payout, with belt-and-suspenders idempotency at both DB and external API layers.
- **SQL Server tuning on multi-million-row tables** — covering indexes, query rewrites, and Dapper multi-mapping with proper `splitOn` for complex joins.

(These live in private company repos, but I'm happy to walk through the architecture in interviews.)

## What I'm building publicly

Pinned repos below. I'm slowly publishing the patterns and techniques I use at work in standalone, reusable form — starting with idempotency helpers and queue-consumer templates.

## Find me

- 💼 **LinkedIn:** [linkedin.com/in/nikamvenkatesh](https://www.linkedin.com/in/nikamvenkatesh)
- 🧠 **LeetCode:** [leetcode.com/u/nikam_venkatesh](https://leetcode.com/u/nikam_venkatesh)
- 📧 **Email:** nikamvenkatesh1@gmail.com

I'm open to mid-level backend / full-stack engineering roles at product companies — Pune, Bangalore, Hyderabad, remote-India, or remote-international.
