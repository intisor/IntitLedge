# The Intitech Reading & Content Grind: Master List

## 1. Hardcore CLR, Memory & Diagnostics (CSC305 / SEN309)
*From visual concepts to nanosecond-level Garbage Collector tuning.*

* **Maarten Balliauw’s Blogs:** Start here for the transition from theory to practice.
    * *Making .NET Code Less Allocatey*
    * *Exploring Memory Allocation and Strings*
* **Pro .NET Memory Management by Konrad Kokosa:** The undisputed bible of .NET internals. Essential for understanding the Large Object Heap (LOH), struct vs. class memory alignment, and zero-allocation architectures.
* **Kevin Gosse (minidump.net / Medium):** Masterclasses on writing .NET profilers, GC mechanics, and analyzing memory dumps (`ClrMD`). 
* **Adam Sitnik’s Blog:** Core contributor to `BenchmarkDotNet`. Heavy reads on `Span<T>`, `Memory<T>`, and low-level hardware intrinsics in C#.
* **JetBrains .NET Blog:** Tutorials on Dynamic Program Analysis (DPA) and profiling. How to read memory dumps instead of guessing why your API is slow.

## 2. Concurrency, Async Mastery & I/O (SEN309 / CSC206)
*For VIIDII WebRTC signaling and handling parallel API requests without destroying the server.*

* **David Fowler’s Asynchronous Guidance (`davidfowl/AspNetCoreDiagnosticScenarios`):** The creator of SignalR visually documents the exact "Do's and Don'ts" of async programming, deadlocks, and Thread Pool starvation. **(MANDATORY)**
* **Stephen Cleary’s Blog & Books:** The godfather of `async/await`. Read: *Concurrency in C# Cookbook*, *There Is No Thread*, and *Don't Block on Async Code*.
* **Marc Gravell’s Blog:** Creator of Dapper. Deep dives into `System.IO.Pipelines` and high-performance socket programming (critical for your WebRTC backends).
* **SignalR Core Documentation (Microsoft Learn):** Deep dive into connection pooling, WebSockets, and real-time state management.

## 3. Enterprise Architecture & System Design (SEN307 / SEN208)
*For designing the AMSA ecosystem so it scales cleanly without spaghetti code.*

* **Designing Data-Intensive Applications by Martin Kleppmann:** The Holy Grail of backend engineering. Teaches how databases handle replication, partitioning, and distributed caching under heavy load.
* **Derek Comartin (CodeOpinion):** Hands down the most pragmatic voice on software architecture. Binge his content on CQRS, Event Sourcing, and why you shouldn't always use the Repository Pattern.
* **Milan Jovanović (The .NET Weekly):** Highly practical C# breakdowns of Clean Architecture, Vertical Slice Architecture, and Outbox Patterns.
* **.NET Microservices: Architecture for Containerized .NET Applications:** Microsoft's official playbook on structuring massive projects using Docker, Service Bus, and clean architecture.
* **Martin Fowler’s Architecture Articles:** Specifically on Event-Driven Architecture.

## 4. Algorithms, High-Performance C# & Low-Level APIs (SEN303 / CSC203 / CSC204)
*Bridging the gap between Big O theory, visual intuition, and raw CPU architecture.*
* **Grokking Algorithms:** The best visual intuition for FUTA's Data Structures and Algorithms.
* **Common-Sense Guide to Data Structures and Algorithms:** Pragmatic, code-first applications of Big O optimization.
* **Stephen Toub’s "Performance Improvements in .NET" (Microsoft DevBlog):** A massive annual blog post by the guy who optimizes C#. Teaches you how the underlying IL (Intermediate Language) and JIT compiler work.
* **Ben Adams (GitHub / Twitter):** Known for insane Kestrel web server optimizations. Studying his Pull Requests is a masterclass in bit manipulation and reducing allocation overhead.

## 5. The "Crack Dev" Daily Intake (YouTube & Blogs)
*Consume these during downtime or to generate ideas for your YouTube Doc-to-Code content.*
* **Nick Chapsas (YouTube):** The best channel for modern C# performance tricks, API design, and benchmarking.
* **Andrew Lock (.NET Escapades):** Incredible deep dives into ASP.NET Core middleware, routing, and underlying framework logic.

## 6. The "Intitech" Business, Scaling & AI Edge (EMT301)
*For branding, pricing your SaaS, and navigating the remote job market.*
* **The Pragmatic Engineer (Gergely Orosz):** The #1 newsletter for understanding how Big Tech operates, writing engineering resumes that get past filters, and negotiating remote contracts.
* **Microsoft Semantic Kernel GitHub Repo / Docs:** Don't just read the tutorials—study the architecture of how Microsoft handles AI plugins and agentic workflows in C#.
