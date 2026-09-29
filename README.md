# Awesome TDK Framework

A curated map of **TDK (Tilt Development Kit)**: the CLI, guides, examples, integrations, and community resources for running a microservice landscape locally with Docker and Tilt.

> [!NOTE]
> This catalog is for the TDK microservice development framework from [tdk-landscape](https://github.com/tdk-landscape). TDK is an independent project built on [Tilt](https://tilt.dev); it is not affiliated with the electronics company also named TDK.

## Contents

- [Start here](#start-here)
- [Core framework and releases](#core-framework-and-releases)
- [Documentation and reference](#documentation-and-reference)
- [Learning and articles](#learning-and-articles)
- [Examples and demo applications](#examples-and-demo-applications)
- [Starters and scaffolding](#starters-and-scaffolding)
- [Integrations and supporting tools](#integrations-and-supporting-tools)
- [Extensions and historical projects](#extensions-and-historical-projects)
- [Community and contribution](#community-and-contribution)
- [Contributing to this catalog](#contributing-to-this-catalog)

## Start here

- [TDK website](https://tdk-landscape.github.io/tdk-website/) — overview, documentation, and project news. **Official**
- [Quickstart](https://tdk-landscape.github.io/tdk-website/docs/quickstart/) — install TDK and run your first local stack. **Official**
- [tdk-cli-core](https://github.com/tdk-landscape/tdk-cli-core) — the main public monorepo for the CLI, Tilt engine, and service discovery. **Official**
- [TDK organization on GitHub](https://github.com/tdk-landscape) — browse public source repositories and releases. **Official**

## Core framework and releases

- [tdk-cli-core](https://github.com/tdk-landscape/tdk-cli-core) — scaffold services and run a local microservice landscape with hot reload and health checks. **Official**
- [CLI quick start and command overview](https://github.com/tdk-landscape/tdk-cli-core#quick-start) — install TDK, create a project, scaffold a resource, and run a stack. **Official**
- [npm package](https://www.npmjs.com/package/@tdk-landscape/tdk-cli-core) — install the TDK CLI with npm or Bun. **Official**
- [tdk-cli-releases](https://github.com/tdk-landscape/tdk-cli-releases/releases) — prebuilt TDK CLI binaries for supported platforms. **Official**
- [tdk-landscape.github.io](https://github.com/tdk-landscape/tdk-landscape.github.io) — source for the public install site and CLI installer. **Official**
- [Install script](https://tdk-landscape.github.io/install.sh) — shell installer for the published CLI binary. **Official**
- [Changelog](https://github.com/tdk-landscape/tdk-cli-core/blob/main/CHANGELOG.md) — notable CLI and framework changes. **Official**

## Documentation and reference

- [TDK documentation](https://tdk-landscape.github.io/tdk-website/) — guides, concepts, and reference material. **Official**
- [Examples guide](https://tdk-landscape.github.io/tdk-website/docs/examples/) — walkthroughs of projects built with TDK. **Official**
- [Core repository README](https://github.com/tdk-landscape/tdk-cli-core#readme) — installation, quick start, architecture, feature overview, and FAQ. **Official**
- [Core repository docs](https://github.com/tdk-landscape/tdk-cli-core/tree/main/docs) — detailed framework documentation. **Official**
- [Contributing to tdk-cli-core](https://github.com/tdk-landscape/tdk-cli-core/blob/main/CONTRIBUTING.md) — development setup and contribution workflow. **Official**
- [Security policy](https://github.com/tdk-landscape/tdk-cli-core/blob/main/SECURITY.md) — responsible vulnerability reporting. **Official**

## Learning and articles

- [TDK blog](https://tdk-landscape.github.io/tdk-website/blog/) — browse the complete official article library. **Official**
- [We Ran 100 Microservices on a 16GB Laptop. No Kubernetes.](https://dev.to/mynameis0d3c53a3/we-ran-100-microservices-on-a-16gb-laptop-no-kubernetes-590e) — TDK overview and reproducible scale benchmark using the 100-service ERP example. **Community**
- [A Better Default for Service Teams](https://tdk-landscape.github.io/tdk-website/blog/articles/a-better-default-for-service-teams/) — Why TDK is built for teams that want standard tools, faster feedback, and less local ceremony. **Official**
- [A Better First Week for Founding Engineers](https://tdk-landscape.github.io/tdk-website/blog/articles/a-better-first-week-for-founding-engineers/) — How early teams can avoid building local infrastructure from scratch before the product is proven. **Official**
- [A Local Registry for Real Teams](https://tdk-landscape.github.io/tdk-website/blog/articles/a-local-registry-for-real-teams/) — Why internal packages and generated clients benefit from a local registry during development. **Official**
- [A Smaller Surface for Mistakes](https://tdk-landscape.github.io/tdk-website/blog/articles/a-smaller-surface-for-mistakes/) — How generated conventions reduce the number of places local setup can quietly drift. **Official**
- [AI Assistants Need Topology](https://tdk-landscape.github.io/tdk-website/blog/articles/ai-assistants-need-topology/) — Why coding assistants behave better when they understand services, boundaries, generated files, and ownership. **Official**
- [Bun, Node, and Practical Defaults](https://tdk-landscape.github.io/tdk-website/blog/articles/bun-node-and-practical-defaults/) — How runtime choices should serve developer feedback instead of becoming identity debates. **Official**
- [C4 Diagrams That Do Not Rot](https://tdk-landscape.github.io/tdk-website/blog/articles/c4-diagrams-that-do-not-rot/) — Why architecture diagrams should be generated from the system instead of redrawn after the fact. **Official**
- [Code Generation That Stays Inspectable](https://tdk-landscape.github.io/tdk-website/blog/articles/code-generation-that-stays-inspectable/) — How generated files can help teams without becoming an opaque maintenance burden. **Official**
- [Configuration That Explains Itself](https://tdk-landscape.github.io/tdk-website/blog/articles/configuration-that-explains-itself/) — Why generated configs should carry enough structure for humans and assistants to understand them. **Official**
- [Counting the Cost of Waiting](https://tdk-landscape.github.io/tdk-website/blog/articles/counting-the-cost-of-waiting/) — Why blocked developers are expensive even before a team buys any extra infrastructure. **Official**
- [Databases Are Part of the App](https://tdk-landscape.github.io/tdk-website/blog/articles/databases-are-part-of-the-app/) — How local database setup, migrations, and service ownership shape daily developer confidence. **Official**
- [Day-One Onboarding for Microservices](https://tdk-landscape.github.io/tdk-website/blog/articles/day-one-onboarding-for-microservices/) — What it should feel like when a new developer joins a service-heavy product team. **Official**
- [Do Not Rewrite Before You Understand](https://tdk-landscape.github.io/tdk-website/blog/articles/do-not-rewrite-before-you-understand/) — Why brownfield modernization starts with discovery, not a heroic platform replacement. **Official**
- [Documentation for Humans and Assistants](https://tdk-landscape.github.io/tdk-website/blog/articles/documentation-for-humans-and-assistants/) — Why modern engineering docs need to serve both people reading and agents acting. **Official**
- [From Empty Repo to Working Landscape](https://tdk-landscape.github.io/tdk-website/blog/articles/from-empty-repo-to-working-landscape/) — How a service landscape forms when definitions, generated artifacts, and local orchestration line up. **Official**
- [From Product Intent to Runnable Services](https://tdk-landscape.github.io/tdk-website/blog/articles/from-product-intent-to-runnable-services/) — How TDK turns service definitions into local systems developers can actually inspect and run. **Official**
- [From Ticket to Topology](https://tdk-landscape.github.io/tdk-website/blog/articles/from-ticket-to-topology/) — How assistants can work better when user stories connect to actual services and generated context. **Official**
- [Frontend and Backend in One Loop](https://tdk-landscape.github.io/tdk-website/blog/articles/frontend-and-backend-in-one-loop/) — Why product work moves faster when UI, API, and generated clients update together. **Official**
- [Generated Clients Without Guesswork](https://tdk-landscape.github.io/tdk-website/blog/articles/generated-clients-without-guesswork/) — How generated SDK and client surfaces reduce drift between frontend and backend work. **Official**
- [Generated Does Not Mean Disposable](https://tdk-landscape.github.io/tdk-website/blog/articles/generated-does-not-mean-disposable/) — How generated artifacts can become stable, reviewable parts of the engineering system. **Official**
- [Golden Layers for Boring Builds](https://tdk-landscape.github.io/tdk-website/blog/articles/golden-layers-for-boring-builds/) — How shared Docker layers can make generated services faster and easier to reason about. **Official**
- [Gradual Adoption Without Drama](https://tdk-landscape.github.io/tdk-website/blog/articles/gradual-adoption-without-drama/) — How teams can bring TDK into an existing repo without stopping product work. **Official**
- [Hot Reload Is a Trust Feature](https://tdk-landscape.github.io/tdk-website/blog/articles/hot-reload-is-a-trust-feature/) — Why developers keep using local tools only when feedback feels immediate and reliable. **Official**
- [How to Review Generated Infrastructure](https://tdk-landscape.github.io/tdk-website/blog/articles/how-to-review-generated-infrastructure/) — A guide to inspecting generated Docker, Tilt, TypeScript, and config outputs with confidence. **Official**
- [Local Credentials Without Spreadsheets](https://tdk-landscape.github.io/tdk-website/blog/articles/local-credentials-without-spreadsheets/) — Why developer secrets need managed paths, not tribal knowledge and old setup docs. **Official**
- [Local First Does Not Mean Local Only](https://tdk-landscape.github.io/tdk-website/blog/articles/local-first-does-not-mean-local-only/) — Why strong local development complements CI, staging, and production instead of replacing them. **Official**
- [Local Tooling and Team Morale](https://tdk-landscape.github.io/tdk-website/blog/articles/local-tooling-and-team-morale/) — Why reliable development environments make engineers more willing to touch unfamiliar services. **Official**
- [Making Brownfield Code Legible](https://tdk-landscape.github.io/tdk-website/blog/articles/making-brownfield-code-legible/) — How discovery can reveal hidden services, missing manifests, and patterns worth preserving. **Official**
- [Microservice Sprawl Needs a Workbench](https://tdk-landscape.github.io/tdk-website/blog/articles/microservice-sprawl-needs-a-workbench/) — Why service count becomes manageable only when developers have a coherent local surface. **Official**
- [Microservices Without Local Theater](https://tdk-landscape.github.io/tdk-website/blog/articles/microservices-without-local-theater/) — How to tell the difference between a useful local stack and a fragile demo. **Official**
- [MIT License as Product Philosophy](https://tdk-landscape.github.io/tdk-website/blog/articles/mit-license-as-product-philosophy/) — Why open licensing matters when a tool sits in the middle of daily engineering work. **Official**
- [MVP Speed Without Throwaway Tooling](https://tdk-landscape.github.io/tdk-website/blog/articles/mvp-speed-without-throwaway-tooling/) — Why fast early product work still deserves a local stack that can survive growth. **Official**
- [NATS in the Development Loop](https://tdk-landscape.github.io/tdk-website/blog/articles/nats-in-the-development-loop/) — Why event-driven services need local messaging support that developers can see and restart. **Official**
- [New Hire Confidence Is a Feature](https://tdk-landscape.github.io/tdk-website/blog/articles/new-hire-confidence-is-a-feature/) — Why the first successful local boot shapes how quickly people feel useful. **Official**
- [No Kubernetes Before Lunch](https://tdk-landscape.github.io/tdk-website/blog/articles/no-kubernetes-before-lunch/) — Why TDK keeps developers productive without asking every product engineer to become a cluster operator. **Official**
- [Observability Starts on the Laptop](https://tdk-landscape.github.io/tdk-website/blog/articles/observability-starts-on-the-laptop/) — Why logs, status, health, and service relationships should be visible before staging. **Official**
- [Owning the Output](https://tdk-landscape.github.io/tdk-website/blog/articles/owning-the-output/) — Why teams should be able to keep every generated file if they outgrow the generator. **Official**
- [Plain Docker Is Still a Feature](https://tdk-landscape.github.io/tdk-website/blog/articles/plain-docker-is-still-a-feature/) — Why standard generated Docker files are easier to inspect, debug, and keep than opaque platform magic. **Official**
- [Playwright Belongs Near the Stack](https://tdk-landscape.github.io/tdk-website/blog/articles/playwright-belongs-near-the-stack/) — Why end-to-end testing is more useful when the local system is easy to boot and reset. **Official**
- [Ports Should Not Be Folklore](https://tdk-landscape.github.io/tdk-website/blog/articles/ports-should-not-be-folklore/) — Why local port assignment belongs in generated configuration instead of memory and Slack. **Official**
- [Postgres as a First-Class Neighbor](https://tdk-landscape.github.io/tdk-website/blog/articles/postgres-as-a-first-class-neighbor/) — How local database services become less painful when they are part of generated orchestration. **Official**
- [Prisma in a Generated Stack](https://tdk-landscape.github.io/tdk-website/blog/articles/prisma-in-a-generated-stack/) — Where ORM setup fits when service definitions generate development infrastructure. **Official**
- [Queues Belong in the Local Story](https://tdk-landscape.github.io/tdk-website/blog/articles/queues-belong-in-the-local-story/) — Why background work and messaging need first-class local support, not production-only mystery. **Official**
- [Secrets Are Not Onboarding Steps](https://tdk-landscape.github.io/tdk-website/blog/articles/secrets-are-not-onboarding-steps/) — How managed identities reduce the habit of copying credentials through unsafe channels. **Official**
- [Selective Startup for Big Repos](https://tdk-landscape.github.io/tdk-website/blog/articles/selective-startup-for-big-repos/) — How teams can work on one slice of a system without booting every service every time. **Official**
- [Service Definitions as Team Contracts](https://tdk-landscape.github.io/tdk-website/blog/articles/service-definitions-as-team-contracts/) — How one service.json can make runtime expectations visible across product and platform work. **Official**
- [Standard Files Beat Platform Lock-In](https://tdk-landscape.github.io/tdk-website/blog/articles/standard-files-beat-platform-lock-in/) — Why teams should keep generated output they can read, edit, commit, and carry forward. **Official**
- [Starlark for Repeatable Local Rules](https://tdk-landscape.github.io/tdk-website/blog/articles/starlark-for-repeatable-local-rules/) — Why small deterministic orchestration rules can beat a pile of custom shell scripts. **Official**
- [Stop Asking AI to Guess Your Architecture](https://tdk-landscape.github.io/tdk-website/blog/articles/stop-asking-ai-to-guess-your-architecture/) — How TDK gives assistants concrete context before they suggest changes in the wrong layer. **Official**
- [tdk doctor as Team Memory](https://tdk-landscape.github.io/tdk-website/blog/articles/tdk-doctor-as-team-memory/) — How health checks can replace long troubleshooting threads with actionable local diagnostics. **Official**
- [Terminal UI for Real Work](https://tdk-landscape.github.io/tdk-website/blog/articles/terminal-ui-for-real-work/) — How a focused terminal interface can make a complex service landscape easier to scan. **Official**
- [Testing the System You Actually Run](https://tdk-landscape.github.io/tdk-website/blog/articles/testing-the-system-you-actually-run/) — How local orchestration can make tests reflect real service relationships instead of isolated assumptions. **Official**
- [The AGENTS.md Advantage](https://tdk-landscape.github.io/tdk-website/blog/articles/the-agents-md-advantage/) — A practical guide to generated assistant briefings and why they matter in larger repos. **Official**
- [The AI Code Review Context Problem](https://tdk-landscape.github.io/tdk-website/blog/articles/the-ai-code-review-context-problem/) — Why reviewers and assistants both need a map of generated files and service boundaries. **Official**
- [The Best Docs Are Rebuilt](https://tdk-landscape.github.io/tdk-website/blog/articles/the-best-docs-are-rebuilt/) — Why documentation that regenerates from service definitions is easier to trust than a wiki page. **Official**
- [The Brownfield Rescue Path](https://tdk-landscape.github.io/tdk-website/blog/articles/the-brownfield-rescue-path/) — How existing repos can be discovered and gradually shaped into explicit service definitions. **Official**
- [The Case for Verdaccio](https://tdk-landscape.github.io/tdk-website/blog/articles/the-case-for-verdaccio/) — How a local package registry supports service-heavy TypeScript development. **Official**
- [The CLI as a Calm Interface](https://tdk-landscape.github.io/tdk-website/blog/articles/the-cli-as-a-calm-interface/) — Why a development CLI should guide without burying engineers under flags and hidden states. **Official**
- [The Cost of Setup Rituals](https://tdk-landscape.github.io/tdk-website/blog/articles/the-cost-of-setup-rituals/) — How repeated onboarding chores quietly consume product time and make teams afraid to change services. **Official**
- [The DevOps Case for TDK](https://tdk-landscape.github.io/tdk-website/blog/articles/the-devops-case-for-tdk/) — How generated local environments keep platform attention closer to production reliability. **Official**
- [The Difference Between Demo and Daily Driver](https://tdk-landscape.github.io/tdk-website/blog/articles/the-difference-between-demo-and-daily-driver/) — What separates a local stack that impresses once from one developers trust every day. **Official**
- [The Difference Between Simple and Simplistic](https://tdk-landscape.github.io/tdk-website/blog/articles/the-difference-between-simple-and-simplistic/) — How TDK tries to reduce local complexity without pretending distributed systems are easy. **Official**
- [The Discipline of Boring Defaults](https://tdk-landscape.github.io/tdk-website/blog/articles/the-discipline-of-boring-defaults/) — Why teams move faster when generated defaults are predictable, readable, and unexciting. **Official**
- [The End of Setup Archaeology](https://tdk-landscape.github.io/tdk-website/blog/articles/the-end-of-setup-archaeology/) — Why developers should not have to reconstruct old setup decisions from scripts and memories. **Official**
- [The Escape Hatch Is the Product](https://tdk-landscape.github.io/tdk-website/blog/articles/the-escape-hatch-is-the-product/) — How no-lock-in design makes a developer tool safer to adopt. **Official**
- [The Fast Path to a Useful Demo](https://tdk-landscape.github.io/tdk-website/blog/articles/the-fast-path-to-a-useful-demo/) — Why a runnable multi-service demo beats screenshots when teams need product feedback. **Official**
- [The First Manifest to Write](https://tdk-landscape.github.io/tdk-website/blog/articles/the-first-manifest-to-write/) — Where to start when turning an existing service into an explicit TDK service definition. **Official**
- [The Founder Case for TDK](https://tdk-landscape.github.io/tdk-website/blog/articles/the-founder-case-for-tdk/) — How TDK reduces setup drag so tiny teams spend more time on customer-facing decisions. **Official**
- [The Hidden Price of Cloud Workspaces](https://tdk-landscape.github.io/tdk-website/blog/articles/the-hidden-price-of-cloud-workspaces/) — Why rented developer environments can solve setup while introducing spend, latency, and governance questions. **Official**
- [The Laptop Should Tell the Truth](https://tdk-landscape.github.io/tdk-website/blog/articles/the-laptop-should-tell-the-truth/) — Why local environments should reveal integration problems early instead of hiding them until CI. **Official**
- [The Local Gateway Pattern](https://tdk-landscape.github.io/tdk-website/blog/articles/the-local-gateway-pattern/) — Why gateways, nginx, and routing deserve generated support in local service landscapes. **Official**
- [The Local Stack as a Product Surface](https://tdk-landscape.github.io/tdk-website/blog/articles/the-local-stack-as-a-product-surface/) — Why internal developer experience deserves the same care as user-facing workflows. **Official**
- [The Local System Is a Contract](https://tdk-landscape.github.io/tdk-website/blog/articles/the-local-system-is-a-contract/) — Why every service should declare how it runs, connects, and participates in the development loop. **Official**
- [The Platform Engineer Case for TDK](https://tdk-landscape.github.io/tdk-website/blog/articles/the-platform-engineer-case-for-tdk/) — Why platform teams should automate local development instead of becoming laptop support. **Official**
- [The Practical Beauty of One Command](https://tdk-landscape.github.io/tdk-website/blog/articles/the-practical-beauty-of-one-command/) — Why one reliable command can be more valuable than a thick setup guide. **Official**
- [The Problem With Perfect Templates](https://tdk-landscape.github.io/tdk-website/blog/articles/the-problem-with-perfect-templates/) — Why templates help only when they keep matching the system after the first generation. **Official**
- [The Problem With Works on My Machine](https://tdk-landscape.github.io/tdk-website/blog/articles/the-problem-with-works-on-my-machine/) — How reproducible generated environments remove a phrase teams should not need anymore. **Official**
- [The Product Engineer Case for TDK](https://tdk-landscape.github.io/tdk-website/blog/articles/the-product-engineer-case-for-tdk/) — How product developers can ship across services without memorizing infrastructure internals. **Official**
- [The Quiet ROI of Fewer Interruptions](https://tdk-landscape.github.io/tdk-website/blog/articles/the-quiet-roi-of-fewer-interruptions/) — How reducing setup questions and environment drift returns attention to product work. **Official**
- [The Real Meaning of Reproducible](https://tdk-landscape.github.io/tdk-website/blog/articles/the-real-meaning-of-reproducible/) — What reproducibility should mean for service discovery, ports, credentials, generated files, and startup. **Official**
- [The Service Registry as Shared Memory](https://tdk-landscape.github.io/tdk-website/blog/articles/the-service-registry-as-shared-memory/) — How a service registry helps teams understand what exists, where it runs, and how it connects. **Official**
- [The Spec Is the Map, Not the Terrain](https://tdk-landscape.github.io/tdk-website/blog/articles/the-spec-is-the-map-not-the-terrain/) — How teams can use specs to reduce ambiguity without confusing written intent for production behavior. **Official**
- [Tilt Without the Cluster Tax](https://tdk-landscape.github.io/tdk-website/blog/articles/tilt-without-the-cluster-tax/) — How TDK uses Tilt and Starlark for local orchestration without forcing Kubernetes concepts into every task. **Official**
- [Traefik Without Mystery](https://tdk-landscape.github.io/tdk-website/blog/articles/traefik-without-mystery/) — How generated routing config can make local service URLs predictable. **Official**
- [Vite Everywhere It Helps](https://tdk-landscape.github.io/tdk-website/blog/articles/vite-everywhere-it-helps/) — How consistent Vite usage can make frontend, backend, SDK, and library workflows easier to reason about. **Official**
- [What Belongs in CI After TDK](https://tdk-landscape.github.io/tdk-website/blog/articles/what-belongs-in-ci-after-tdk/) — How local reproducibility changes what teams expect from continuous integration. **Official**
- [What SDD Cannot Do](https://tdk-landscape.github.io/tdk-website/blog/articles/what-sdd-cannot-do/) — Why specs cannot replace product judgment, architecture tradeoffs, operational feedback, or integration testing. **Official**
- [What SDD Gets Right](https://tdk-landscape.github.io/tdk-website/blog/articles/what-sdd-gets-right/) — The useful parts of spec-driven development: shared language, reviewable intent, and better AI handoffs. **Official**
- [When Cloud Development Makes Sense](https://tdk-landscape.github.io/tdk-website/blog/articles/when-cloud-development-makes-sense/) — A fair look at where cloud workspaces help and where local tooling remains simpler. **Official**
- [When Specs Lie Quietly](https://tdk-landscape.github.io/tdk-website/blog/articles/when-specs-lie-quietly/) — A practical look at stale assumptions, missing edge cases, and the false comfort of tidy requirements. **Official**
- [When the Stack Should Say No](https://tdk-landscape.github.io/tdk-website/blog/articles/when-the-stack-should-say-no/) — Why good local tooling should fail early, explain clearly, and avoid partial mystery states. **Official**
- [Why AI Needs Guardrails, Not Theater](https://tdk-landscape.github.io/tdk-website/blog/articles/why-ai-needs-guardrails-not-theater/) — The practical role of generated boundaries, ownership notes, and service maps in AI-assisted coding. **Official**
- [Why Big Repos Need Small Rituals](https://tdk-landscape.github.io/tdk-website/blog/articles/why-big-repos-need-small-rituals/) — How simple repeated commands can hold a large service graph together. **Official**
- [Why Generated Docs Beat Forgotten Docs](https://tdk-landscape.github.io/tdk-website/blog/articles/why-generated-docs-beat-forgotten-docs/) — How generated C4 diagrams and assistant briefings keep documentation closer to the live system. **Official**
- [Why Local Dev Needs Product Design](https://tdk-landscape.github.io/tdk-website/blog/articles/why-local-dev-needs-product-design/) — Internal tools still have users, workflows, friction, and moments where clarity matters. **Official**
- [Why Local Feedback Still Wins](https://tdk-landscape.github.io/tdk-website/blog/articles/why-local-feedback-still-wins/) — The case for fast local loops even when cloud development environments look convenient on paper. **Official**
- [Why One Manifest Matters](https://tdk-landscape.github.io/tdk-website/blog/articles/why-one-manifest-matters/) — The benefits of giving each service one explicit source for local development intent. **Official**
- [Why TDK Does Not Hide the Stack](https://tdk-landscape.github.io/tdk-website/blog/articles/why-tdk-does-not-hide-the-stack/) — TDK exposes standard tools because hiding every detail makes teams weaker when debugging starts. **Official**
- [Why TDK Is Not a Cloud IDE](https://tdk-landscape.github.io/tdk-website/blog/articles/why-tdk-is-not-a-cloud-ide/) — The difference between renting a remote machine and generating a better local development surface. **Official**
- [Why TDK Matters After the Spec](https://tdk-landscape.github.io/tdk-website/blog/articles/why-tdk-matters-after-the-spec/) — A closing argument for pairing spec-driven thinking with a development workbench that can actually run the system. **Official**

- [TDK demo animation](https://tdk-landscape.github.io/tdk-demo-animation/) — short visual tour of the CLI workflow and generated project. **Official**

## Examples and demo applications

- [tdk-example](https://github.com/tdk-landscape/tdk-example) — small project demonstrating the Project-Stack-Resource model. **Official**
- [tdk-saas-starter](https://github.com/tdk-landscape/tdk-saas-starter) — SaaS dashboard starter with a working checkout flow. **Official**
- [tdk-restaurant-example](https://github.com/tdk-landscape/tdk-restaurant-example) — restaurant operations example covering reservations, kitchen pacing, menu availability, and floor control. **Official**
- [tdk-ecommerce-example](https://github.com/tdk-landscape/tdk-ecommerce-example) — Vue storefront and Hono catalog API built with TDK. **Official**
- [tdk-auth-queue-email-example](https://github.com/tdk-landscape/tdk-auth-queue-email-example) — local identity, queue, and email example with an OIDC emulator, NATS JetStream, and Mailpit. **Official**
- [tdk-user-management](https://github.com/tdk-landscape/tdk-user-management) — identity and user-management demo organized into TDK stacks. **Official**
- [tdk-erp-system](https://github.com/tdk-landscape/tdk-erp-system) — 100-service ERP fixture across seven business domains, used for scale testing. **Official**
- [tdk-docker-compose-example](https://github.com/tdk-landscape/tdk-docker-compose-example) — example of using the TDK CLI from Docker Compose. **Official**

## Starters and scaffolding

- [create-tdk-stack](https://github.com/tdk-landscape/create-tdk-stack) — starter generator and landing page for creating a TDK stack. **Official**
- [SaaS starter](https://github.com/tdk-landscape/tdk-saas-starter) — start from a multi-service account dashboard with checkout. **Official**
- [Example projects](https://github.com/tdk-landscape?tab=repositories&q=example) — browse public TDK example repositories. **Official**

## Integrations and supporting tools

- [Tilt](https://tilt.dev/) — local development orchestration that TDK configures and runs. **External project**
- [Docker](https://www.docker.com/) — container runtime used by TDK's local development workflow. **External project**
- [Traefik](https://traefik.io/traefik/) — local ingress and routing used in TDK examples. **External project**
- [Bun](https://bun.sh/) — JavaScript runtime used by generated services and supported for CLI installation. **External project**
- [Vue](https://vuejs.org/) — frontend framework used by the ecommerce and auth/queue/email examples. **External project**
- [Hono](https://hono.dev/) — web framework used by TDK backend examples. **External project**
- [NATS](https://nats.io/) — messaging system demonstrated with JetStream in the auth/queue/email example. **External project**
- [PostgreSQL](https://www.postgresql.org/) — database used in TDK's local platform examples. **External project**

## Extensions and historical projects

- [tdk-discovery](https://github.com/tdk-landscape/tdk-discovery) — **Archived.** Earlier standalone service-discovery repository; current development is in [tdk-cli-core](https://github.com/tdk-landscape/tdk-cli-core).
- [tdk-ext](https://github.com/tdk-landscape/tdk-ext) — **Archived.** Earlier extensions repository; use the current [tdk-cli-core extension documentation](https://github.com/tdk-landscape/tdk-cli-core/tree/main/ext) for current work.
- [tdk](https://github.com/tdk-landscape/tdk) — **Archived.** Earlier platform specifications and generators repository; consult the current core repository and website for maintained material.

## Community and contribution

- [TDK organization](https://github.com/tdk-landscape) — official public repositories and projects.
- [Open an issue on tdk-cli-core](https://github.com/tdk-landscape/tdk-cli-core/issues) — ask questions, report a bug, or suggest a framework improvement.
- [Good first issues](https://github.com/tdk-landscape/tdk-cli-core/labels/good%20first%20issue) — beginner-friendly ways to contribute to the core project.

## Contributing to this catalog

Suggestions are welcome through [issues](https://github.com/tdk-landscape/awesome-tdk-framework/issues) or pull requests. Add one concise entry under the best-fitting heading:

```text
- [Project or resource](https://canonical-public-url) — what it is and why it is useful. **Official**, **Community**, or **Archived**
```

Include resources that are publicly accessible, directly useful to people using or extending TDK, and described accurately. Prefer canonical links, avoid duplicates, and disclose whether a resource is official or community-maintained. Mark archived or unmaintained projects clearly. Maintainers may ask for context, move an entry, or decline links that are inaccessible, unrelated, promotional, or no longer useful.
