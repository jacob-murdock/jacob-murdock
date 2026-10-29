# Jacob Murdock

I build systems software, games, and edge web apps, mostly in C. Before this I was an IT analyst at Occidental, where I built integrations between OSIsoft PI, SQL Server and .NET applications. I also went to seminary for a few years, earning a Master of Theology degree and completing 120 graduate credit hours. I sometimes publish under the name Apellus Magnus.

## Projects

**[libresend](https://github.com/jacob-murdock/libresend)**
An unofficial C SDK for the [Resend](https://resend.com) email API. It covers sending, batches, scheduling, attachments, domains, API keys and webhook verification. It's built on libcurl and tested against a fake server in CI on gcc, clang, sanitizers, macOS and MinGW.

**Taxis Kanban** *(https://github.com/jacob-murdock/taxis-kanban)*
A realtime multi-user kanban board on Cloudflare Workers. D1 stores the boards, and Durable Objects handle live sync between users.

**[herald-broker](https://github.com/jacob-murdock/herald-broker)**
A small WebSocket room relay in one C file. It handles rooms, fan-out and late-join catch-up, keeps slow peers from holding up the room, and never parses payloads. It runs multiplayer for Daggermap.

## Private work I'm glad to talk through

- **[Daggermap](https://daggermap.com)**: a cross-platform tabletop map and encounter app. It's written in C, uses the GPU for rendering (and video decode when possible), includes a relay-based multiplayer with N-way P2P enabled by default, and is tightly packaged. It's released on Steam, and I have Android and iOS builds that are currently unreleased.
- **[daggerheartsrd.com](https://daggerheartsrd.com)**: a Daggerheart rules reference on Cloudflare, with accounts and Stripe supporter subscriptions.
- **Droppin' Eaves**: a monitoring and alerting app featuring optional LLM interfaces for users. Internally, it has half a dozen different LLM jobs, tool calls to make them work with adequate context, and a highly performant server architecture.

## Contact

[jacobdmurdock@gmail.com](mailto:jacobdmurdock@gmail.com)
