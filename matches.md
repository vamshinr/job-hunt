# Job Matches — For Review

> Maintained by the 3x-daily cloud job-search routine.
> Each entry is a **genuine new match** against `Search-brief.md`.
> **Nothing is ever submitted.** Review each, then mark Apply / Save / Skip yourself.

---

## Seen-Roles Index

> Dedup ledger. The routine checks this before adding a new match so roles aren't repeated.
> Format: `- <company> | <title> | <location> | <first-seen YYYY-MM-DD> | <application-url>`

<!-- SEEN-INDEX-START -->
- Together AI | Machine Learning Engineer - Inference | San Francisco, CA | 2026-06-28 | https://job-boards.greenhouse.io/togetherai/jobs/4385540007
- Scale AI | Senior AI Infrastructure Engineer, Model Serving Platform | San Francisco / New York / Seattle | 2026-06-28 | https://job-boards.greenhouse.io/scaleai/jobs/4520320005
- Fireworks AI | Member of Technical Staff, Performance Optimization | San Mateo, CA | 2026-06-28 | https://job-boards.greenhouse.io/fireworksai/jobs/4001152009
- Perplexity AI | AI Inference Engineer | San Francisco, CA | 2026-06-28 | https://jobs.ashbyhq.com/perplexity/8a976851-9bef-4b07-8d36-567fa9540aef
- Perplexity AI | AI Infra Engineer (MTS) | San Francisco / Palo Alto, CA | 2026-06-28 | https://jobs.ashbyhq.com/perplexity/598e1f7d-b802-4de2-99ac-90eb2bc33315
<!-- SEEN-INDEX-END -->

---

## New Matches

<!-- New match entries are appended below, newest first. -->

---
*Run: 2026-06-28 — 5 new matches*

---

### Together AI — Machine Learning Engineer - Inference

**Location:** San Francisco, CA (hybrid; confirm remote eligibility)
**Seniority:** Mid-Senior (3+ years required)
**Application Link:** https://job-boards.greenhouse.io/togetherai/jobs/4385540007
**Match Score:** 9/10

## **Why this is a match:**

* Core job is optimizing LLM inference systems powering the Together AI platform — exactly the work Vamshi has done with OpenVINO, ONNX Runtime, vLLM, and TensorRT-LLM at Intel.
* Stack (Python, PyTorch, vLLM, TensorRT-LLM, TGI, CUDA/Triton, speculative decoding, quantization) maps almost perfectly to Vamshi's background.
* Together AI is a priority company; the Inference Engine team is building production systems at the frontier of LLM serving scale.
* 3+ year requirement is a realistic bar (Intel AI/ML + Phenom + KVForge experience covers this cleanly).
* Signals hit: LLM inference optimization, model serving at scale, distributed systems, GPU/CUDA/Triton, benchmarking/latency/throughput, Python + systems programming = 6+ of 10 strong-match signals.

## **Possible concerns:**

Role is listed as San Francisco-based; confirm whether hybrid remote or fully in-office is required before applying. The "Distributed ML Systems Engineer - Inference" role at Together AI was removed in January 2026 — verify this separate "Machine Learning Engineer - Inference" posting is still active before submitting.

**120-word tailored cover letter:**
Together AI's mission to democratize high-performance AI inference is exactly the problem space I'm most energized to work on. At Intel, I spent years optimizing LLM inference pipelines using OpenVINO, ONNX Runtime, and CUDA—squeezing latency and improving throughput across diverse hardware. Through KVForge, I built KV cache optimization strategies that address the memory bandwidth bottlenecks central to large-scale LLM serving. I've worked hands-on with vLLM and TensorRT-LLM and understand the engineering tradeoffs in continuous batching, speculative decoding, and quantization. Your inference engine powers some of the most demanding AI workloads in production, and I'd bring both low-level GPU systems depth and distributed infrastructure experience to help push its performance further. I'd love to contribute to Together AI's next chapter.

## **3 resume bullet tweaks:**

* **Intel AI/ML Software Engineer →** "Optimized LLM inference pipelines using OpenVINO and ONNX Runtime on Intel hardware, profiling end-to-end throughput and latency to meet production SLA targets and guide quantization trade-off decisions."
* **KVForge →** "Built KV cache management and eviction strategies for LLM serving, reducing peak GPU memory pressure during continuous batching scenarios while sustaining generation quality across diverse sequence lengths."
* **Intel AI/ML Software Engineer →** "Developed benchmarking harnesses for LLM inference frameworks (vLLM, TensorRT-LLM), instrumenting throughput and latency across model architectures to surface bottlenecks and validate optimization impact."

**Recommended action:** Apply

---

### Scale AI — Senior AI Infrastructure Engineer, Model Serving Platform

**Location:** San Francisco / New York / Seattle (on-site or hybrid; not explicitly remote)
**Seniority:** Senior (5+ years required)
**Application Link:** https://job-boards.greenhouse.io/scaleai/jobs/4520320005
**Match Score:** 9/10

## **Why this is a match:**

* Role is explicitly about designing platforms for scalable, reliable, efficient serving of LLMs — the most direct title match for Vamshi's positioning as an AI Infrastructure / Model Serving engineer.
* Stack includes vLLM, SGLang, TensorRT-LLM, Python/Go/Rust/C++, Docker, Kubernetes — high overlap with Intel and KVForge background.
* Salary ($216k–$270k) and priority company status (Scale AI) make this a top-tier opportunity.
* Signals hit: LLM serving, model serving platform, AI infrastructure, distributed systems, Python+systems, enterprise AI platform/developer tooling, latency/throughput optimization = 7+ of 10 strong-match signals.
* LLM serving and routing fundamentals (rate limiting, token streaming, load balancing) are the core of the job — directly relevant to KVForge KV cache routing work.

## **Possible concerns:**

Role is posted for SF/NYC/Seattle with no explicit remote option; candidate would need to confirm hybrid policy. 5+ years experience bar is higher than average for this type of role — Vamshi should ensure Intel AI/ML + Phenom + project experience adds up to a credible 5-year story.

**120-word tailored cover letter:**
Scale AI's model serving platform sits at the intersection of two things I care deeply about: reliable production AI infrastructure and making LLMs performant at scale. At Intel, I designed and optimized inference pipelines using TensorRT-LLM, OpenVINO, and ONNX Runtime, and ran end-to-end benchmarks that guided architecture decisions across model families. At KVForge, I built KV cache management and routing systems that improved memory efficiency in continuous batching workloads. I'm experienced with vLLM, Kubernetes, and the distributed systems patterns powering high-throughput model serving. Scale AI's platform supports both internal research and external customer-facing LLM APIs — requiring exactly the systems depth and platform engineering discipline I bring. I'm motivated by the challenge of building reliable serving infrastructure at this scale and would be proud to contribute to this team.

## **3 resume bullet tweaks:**

* **Intel AI/ML Software Engineer →** "Designed and deployed scalable LLM serving infrastructure integrating TensorRT-LLM and ONNX Runtime backends behind Kubernetes-orchestrated serving APIs, supporting production model deployments for internal and partner use cases."
* **KVForge →** "Architected KV cache routing and load-balancing systems for multi-tenant LLM serving, optimizing cache hit rates and reducing per-request compute cost in continuous batching environments under high concurrency."
* **Phenom ML Engineer →** "Built production ML platform infrastructure supporting inference endpoints, real-time scoring pipelines, and model lifecycle management for enterprise-scale deployments serving millions of API requests."

**Recommended action:** Apply

---

### Fireworks AI — Member of Technical Staff, Performance Optimization

**Location:** San Mateo, CA (Bay Area; on-site; no remote indicated)
**Seniority:** Senior (5+ years required)
**Application Link:** https://job-boards.greenhouse.io/fireworksai/jobs/4001152009
**Match Score:** 9/10

## **Why this is a match:**

* Core work is GPU kernel optimization, LLM/VLM inference performance, and distributed inference systems — the tightest possible alignment with Vamshi's Intel background in OpenVINO, CUDA, Nsight, and quantization.
* Stack: CUDA/ROCm, PyTorch, Triton, torch.compile, GPU profiling (Nsight, nvprof, CUPTI), Kubernetes, Ray — almost the exact toolchain from Intel's AI acceleration work.
* Degree minimum is Bachelor's (Master's/PhD preferred but not required); Intel experience clearly substitutes.
* Signals hit: LLM inference optimization, model serving, AI infrastructure, distributed systems, GPU/CUDA/Triton kernels, profiling/benchmarking/latency, Python+systems = 7+ of 10 strong-match signals.
* Fireworks AI is a priority company; Series C ($4B valuation), engineering-first culture focused on squeezing performance from LLM serving.

## **Possible concerns:**

Role is listed in San Mateo, CA with no mention of remote — requires Bay Area presence. Master's/PhD listed as preferred; Intel + KVForge experience should substitute convincingly but worth addressing directly in a cover letter. Confirm posting is still live (was indexed May 2026).

**120-word tailored cover letter:**
Fireworks AI's commitment to pushing performance boundaries across the LLM and VLM inference stack is exactly the kind of deep, high-impact engineering I've been building toward. At Intel, I worked on the front lines of AI acceleration — profiling CUDA kernel execution with Nsight Systems and CUPTI, implementing quantization schemes (INT8, FP8) that cut model size and improved throughput, and optimizing transformer inference on GPU hardware. Through KVForge, I built CUDA-aware KV cache management systems that improved memory layout efficiency during autoregressive generation. The example projects listed — asynchronous LLM sampling, low-precision GPU kernels, and cache-efficient distributed routing — are problems I've directly engaged with. I'm excited by Fireworks' engineering culture and the opportunity to drive inference performance improvements that benefit production AI workloads at scale.

## **3 resume bullet tweaks:**

* **Intel AI/ML Software Engineer →** "Profiled and optimized GPU kernel execution for LLM inference using Nsight Systems and CUPTI, identifying memory bandwidth bottlenecks and kernel scheduling inefficiencies to reduce end-to-end inference latency on Intel and NVIDIA hardware."
* **Intel AI/ML Software Engineer →** "Implemented INT8 and FP8 quantization pipelines for large language models using OpenVINO and ONNX Runtime, reducing model memory footprint while sustaining accuracy targets across diverse benchmark suites."
* **KVForge →** "Built CUDA-aware KV cache management systems for transformer LLM serving, optimizing memory layout and access patterns to maximize GPU DRAM utilization and reduce memory pressure during high-concurrency autoregressive generation."

**Recommended action:** Apply

---

### Perplexity AI — AI Inference Engineer

**Location:** San Francisco, CA (hybrid; on-site likely required)
**Seniority:** Senior
**Application Link:** https://jobs.ashbyhq.com/perplexity/8a976851-9bef-4b07-8d36-567fa9540aef
**Match Score:** 8/10

## **Why this is a match:**

* Role is literally "building and running the inference engine behind every Perplexity query" — deploying dozens of model architectures at scale under tight latency and cost budgets.
* Stack (Rust, Python, CUDA, CuTe DSL, PyTorch, Triton, Kubernetes) and focus areas (continuous batching, quantization, GPU kernel programming) align directly with Intel and KVForge experience.
* $190k–$250k compensation; Perplexity is a priority company operating one of the highest-throughput AI query systems in the world.
* Signals hit: LLM inference, model serving at scale, distributed systems, GPU/CUDA/Triton, profiling/latency/throughput optimization, Python+systems programming = 6+ of 10 strong-match signals.

## **Possible concerns:**

Rust is a first-class language on this team (stack is Rust + Python + CUDA); Vamshi's primary stack is Python/C++ — Rust proficiency would need to be credibly addressed or developed quickly. Role appears SF in-office; confirm hybrid or remote flexibility. Perplexity's team is small and moves fast — high-output environment.

**120-word tailored cover letter:**
Every Perplexity query demands inference that is fast, accurate, and cost-efficient — building systems that deliver that at millions-of-queries-per-day scale is one of the most compelling engineering challenges in AI today. At Intel, I worked extensively on LLM inference optimization: implementing quantization pipelines, profiling CUDA kernel execution, and tuning throughput-latency tradeoffs in production deployments. At KVForge, I built KV cache eviction and compression systems that reduced memory pressure during continuous batching. I've worked with vLLM, TensorRT-LLM, and CUDA at a systems level, and I'm energized by Perplexity's inference stack combining Python and CUDA with low-level performance engineering. I'm drawn to Perplexity because inference performance engineering here directly translates to user experience at massive scale — and I'm motivated to push that further.

## **3 resume bullet tweaks:**

* **Intel AI/ML Software Engineer →** "Optimized end-to-end LLM inference pipelines using OpenVINO, ONNX Runtime, and TensorRT-LLM, benchmarking throughput and latency across model architectures to meet latency SLAs and guide quantization trade-off decisions in production deployments."
* **KVForge →** "Built KV cache compression and eviction systems for LLM serving, directly reducing memory pressure during continuous batching and enabling higher concurrent request throughput on fixed GPU fleets."
* **Intel AI/ML Software Engineer →** "Profiled CUDA kernel execution for transformer models using Nsight tools, identifying memory bandwidth bottlenecks and implementing optimizations that improved GPU utilization and reduced time-to-first-token latency across diverse model sizes."

**Recommended action:** Apply

---

### Perplexity AI — AI Infra Engineer (Member of Technical Staff)

**Location:** San Francisco / Palo Alto, CA (hybrid; London variant also listed)
**Seniority:** Senior (3–5 years required)
**Application Link:** https://jobs.ashbyhq.com/perplexity/598e1f7d-b802-4de2-99ac-90eb2bc33315
**Match Score:** 8/10

## **Why this is a match:**

* Role owns large-scale Kubernetes cluster management for LLM inference and training workloads at Perplexity — directly relevant to Intel's K8s-based ML serving infrastructure work.
* Stack (Kubernetes, Slurm, Python, C++, PyTorch, AWS) is a direct match to Vamshi's background; 3–5 year experience bar is realistic.
* Salary $190k–$250k; priority company; role sits between infra and ML, partnering with Inference and Research teams.
* Signals hit: AI infrastructure, model serving clusters, LLM inference/training scale, distributed systems, GPU infrastructure management, Python+systems = 5+ of 10 strong-match signals.

## **Possible concerns:**

Primary focus is Kubernetes/Slurm cluster ops (not ML model work itself) — this is infrastructure-heavy; Vamshi's strongest positioning is inference optimization, so this role is slightly left of center. Slurm experience not explicitly mentioned in brief; may need to address. Confirm whether hybrid in-person required at SF/Palo Alto.

**120-word tailored cover letter:**
Building and operating the infrastructure that powers large-scale LLM training and inference at Perplexity requires the intersection of deep ML systems knowledge and production-grade distributed infrastructure expertise — and it's exactly the work I've been doing throughout my career. At Intel, I designed Kubernetes-based ML serving infrastructure, implemented resource scheduling for inference workloads, and built orchestration tooling integrating PyTorch distributed training and inference backends on cloud infrastructure. My experience spans Python and C++ for performance-critical systems, Kubernetes for orchestration, and GPU cluster management for heterogeneous compute environments. Perplexity runs one of the world's highest-throughput AI query systems, and I'd love to help build the reliable, scalable cluster infrastructure that gives its researchers and engineers fast iteration cycles and production-grade serving at scale.

## **3 resume bullet tweaks:**

* **Intel AI/ML Software Engineer →** "Designed and maintained Kubernetes-based ML infrastructure for inference and training workloads, implementing autoscaling policies and resource scheduling configurations to optimize GPU cluster utilization across heterogeneous hardware environments."
* **Intel AI/ML Software Engineer →** "Built orchestration APIs and automation tooling in Python and C++ for distributed ML workloads, integrating with PyTorch distributed training frameworks and multi-backend inference serving systems on AWS infrastructure."
* **Phenom ML Engineer →** "Implemented telemetry and observability instrumentation across production ML serving pipelines, enabling real-time performance monitoring, resource utilization tracking, and anomaly detection across distributed inference clusters."

**Recommended action:** Apply
