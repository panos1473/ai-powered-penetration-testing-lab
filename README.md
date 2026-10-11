AI-Powered Penetration Testing Lab

Overview

This repository documents hands-on experiments in AI-assisted web application penetration testing, conducted as part of my MSc research in Computer Science.

The project investigates how AI-powered tools can identify web application vulnerabilities, execute security tests, and provide evidence-based findings.

All experiments are conducted in an authorized, isolated laboratory environment.

Lab Environment

- Operating System: Kali Linux (VirtualBox)
- Target Application: Damn Vulnerable Web Application (DVWA)
- Containerization: Docker
- AI Security Tool: PentestGPT
- AI Backend: OpenAI Codex
- Target Security Level: DVWA Low

## Completed Experiments

| # | Experiment | Result |
| 01 | Web Application Reconnaissance | Completed |
| 02 | Boolean-Based SQL Injection | Vulnerability detected |
| 03 | Reflected Cross-Site Scripting (XSS) | Vulnerability detected |

Methodology

Each experiment follows a consistent workflow:

1. Configure the authorized test environment.
2. Define a security testing objective.
3. Execute PentestGPT with the Codex backend.
4. Review execution logs and HTTP responses.
5. Validate findings against observable evidence.
6. Document results, limitations, and execution time.

Initial Findings

PentestGPT successfully identified the DVWA application and its login page during reconnaissance.

During SQL injection testing, the tool observed different application responses to true and false SQL conditions, providing evidence of Boolean-based SQL injection.

During reflected XSS testing, the tool observed an unencoded JavaScript payload in the HTTP response. JavaScript execution was also independently verified through a manual browser test.

One XSS testing attempt was blocked by a tool execution issue, after which a subsequent attempt completed successfully.

Project Status

Ongoing research.Additional vulnerability assessments, experimental evidence, and comparative analysis will be added as the project progresses.

Ethical Disclaimer

All security testing is performed exclusively against intentionally vulnerable applications in a controlled, authorized lab environment. No unauthorized systems are targeted.
