# Title: Certifying AI Agents Under the Common Criteria and Emerging Assurance Frameworks
**Preprint.** Submitted to Computer Standards & Interfaces (CSI-D-26-01631),
desk-rejected October 2026. Under revision. Archived at Zenodo: [DOI]

## Abstract

Enterprise deployment of autonomous AI agents has accelerated faster than formal standardization. 
While emerging industry-led standards (such as AIUC-1) bind controls to executable adversarial evidence rather than policy attestations, they suffer from critical structural limitations: non-monotone assurance reporting, absent compositional interfaces for foundation model vendors, loss of cross-evaluation comparability, and unquantified error in LLM-based measurement instruments. On the other hand, formal cybersecurity frameworks like the Common Criteria (ISO/IEC 15408:2022) offer established compositional methodology and graded assurance, but rely on assumptions that agentic systems fundamentally violate for determinism, decomposability of security functions, and stable target configurations.

This paper analyzes the emerging landscape of AI agent security certification. We systematize five core mismatches between formal security standards and agentic systems, and identify four gaps in current empirical evaluation pipelines. Then, we synthesize a unified adaptation framework designated AICC. AICC establishes: (1) the *Boundary Isolation*, placing stochastic models outside the Target of Evaluation (TOE) boundary with complete egress-path mediation; (2) a *Three-Role Composition Model* adapting smartcard composite methodology; (3) *Statistical Conformance and Metrological Qualification* for LLM judges with propagated confusion matrices; and (4) an *Agent Evaluation Assurance Level (AEAL)* tied to autonomy and blast radius. Finally, we provide a unified taxonomy mapping OWASP Agentic Top 10 threats to Security Functional Requirements (SFRs) and crosswalk AICC against the EU AI Act, EUCC, and AIUC-1. 
