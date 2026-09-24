> **Historical 2025 R2PQ prototype lineage.** This repository preserves
> earlier exploratory work. It does not represent the architecture or
> capabilities of the current R2PQ cryptographic-assessment research system.
> Documentation below records historical implementation, limitations,
> and intentions; planned features must not be treated as delivered.
> Current public scope and evidence boundaries: [r2pq.dev](https://r2pq.dev).

## Historical prototype documentation — 2025

README.md

# r2pq-bench

R2PQ Bench is the benchmarking and performance analysis suite for the R2PQ ecosystem.  
Its purpose is to stress-test post-quantum primitives, measure throughput across multiple configurations, and validate stability under load.

## Purpose
- Benchmark R2PQ verification and signing operations  
- Measure end-to-end latency of PQ transactions  
- Analyze performance of R2PQ-SDK and R2PQ-CLI calls  
- Provide reproducible test scripts and outputs  
- Support CI-based benchmarking for performance regression detection  

## Structure

/benchmarks       # Benchmark scripts /results          # Generated reports and logs /config           # Test profiles (CPU, GPU, hybrid)

## Getting Started
Setup instructions will be added after the first implementation pass.

## Status
✅ Initialized  
🚧 Awaiting first code push

# Legal
R2PQ is open-source under the Apache-2.0 License.  
R2PQ™ is a trademark of Eric James Newman.  
See `LICENSE`, `NOTICE`, and `TRADEMARKS.md` for details.
