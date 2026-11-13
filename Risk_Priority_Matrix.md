# AI Identity Security – Risk Priority Matrix

## Project 3 – Red Team Findings

**Assessment type:** Preliminary qualitative risk assessment  
**Note:** Priorities are provisional. The Project 3 tests were simulations and do not establish successful live exploitation. CVSS scores require further validation.

 1. Risk Assessment

| Finding | Likelihood | Impact | Preliminary Priority |
|---|---|---|---|
| Indirect Prompt Injection | High | High | High |
| Agent Identity Spoofing | Medium | High | High |
| System Prompt Extraction | Medium | Medium | Medium |
| RAG Poisoning | High | High | High |
| MCP Tool Abuse | Medium | High | Critical |

## 2. Risk Priority Matrix

| Impact / Likelihood | Low Likelihood | Medium Likelihood | High Likelihood |
|---|---|---|---|
| **High Impact** | — | Agent Identity Spoofing; MCP Tool Abuse | Indirect Prompt Injection; RAG Poisoning |
| **Medium Impact** | — | System Prompt Extraction | — |
| **Low Impact** | — | — | — |

## 3. CVSS Assessment

CVSS scores and vector strings: **Pending validation**.

The available simulated test results are insufficient to assign verified CVSS scores.

## 4. Recommended Actions

1. Implement input and output guardrails.
2. Enforce cryptographic agent identity verification.
3. Restrict agent permissions using least privilege.
4. Monitor suspicious prompts and tool activity.
5. Review and secure RAG data sources and MCP tool access.
