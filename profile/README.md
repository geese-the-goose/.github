<p align="center">
  <img src="https://raw.githubusercontent.com/geese-the-goose/goose/main/assets/geese-flying.gif" width="100%" alt="Geese the Goose">
</p>

# Geese the Goose

Building foundational systems and networking infrastructure for the Goose programming language.

Geese the Goose is an open-source organization focused on systems software, asynchronous runtimes, networking, developer infrastructure, and experimental low-level tooling around Goose. Our work is in early development, with an emphasis on clear architecture and foundations that can be tested against practical workloads.

## Projects

### [Goose](https://github.com/geese-the-goose/goose)

An asynchronous runtime and networking foundation for Goose, intended for efficient systems and long-running networked applications.

Goose is in early development. The repository currently contains project documentation and branding; the runtime, networking capabilities, and public API are not yet implemented.

## Direction

Our long-term technical direction includes:

- Event-driven I/O, asynchronous task scheduling, timers, and timeouts.
- TCP and UDP networking, backpressure, and reconnect logic.
- Synchronization primitives and cancellation with explicit lifecycle behavior.
- Utilities and codecs, with higher-level protocols kept separate from the core runtime.
- Testing infrastructure and reproducible benchmarks for correctness, reliability, and resource use.
- Constrained-device workloads and long-running network services.

These are planned areas of work, not claims of current capability or platform support.

## Design Principles

- Build small, composable foundations.
- Make resource ownership explicit.
- Aim for predictable performance and minimal overhead.
- Treat production-oriented reliability as a design goal that must be demonstrated through testing.
- Evolve across platforms through clear interfaces and validated backends.
- Maintain strong testing discipline and measure performance with reproducible benchmarks.
- Keep the core runtime separate from higher-level protocols.

## Current Status

The organization and runtime are in early development. Architecture and scope are being defined; APIs, once introduced, are expected to evolve. There are no runtime releases or production-readiness guarantees at this stage.

## Why Goose?

We want to explore serious systems and networking infrastructure for the Goose language while keeping the architecture practical, measurable, and useful for real applications.

## Real-world Workloads

One intended reference workload is a long-running CCTV and networking system with persistent connections, reconnects, control messages, streaming-oriented traffic, constrained hardware, and reliability testing. It offers concrete constraints for evaluating design choices alongside broader systems and networking applications.

## Contributing

Contribution guidelines will be published as the project matures. Visit the [Goose repository](https://github.com/geese-the-goose/goose) to follow development, review the current direction, and discuss focused proposals.

## Security

Security issues should be reported privately. A formal security policy and private reporting instructions will be added to the project repositories. Until a reporting channel is published, do not include sensitive vulnerability details in public issues; request a private contact channel without disclosing those details.

## Organization

As the work develops, the organization will contain separate repositories for runtime components, utilities, protocols, testing, documentation, and related infrastructure where that separation serves a clear purpose.
