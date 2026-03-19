# OpenClaw-Guard-ai

Description:
- Build an AI-assisted DevSecOps tool that analyzes npm packages before installation and flags supply-chain threats such as malicious lifecycle hooks, suspicious script execution, credential-targeting file access, obfuscation, and remote payload delivery


Why this is relevant:
- With the new trend of countless users installing OpenClaw and using its agentic capabilities malicious package installation is a high risk factor for companies looking to incorporate OpenClaw. From an online forum JFrog reported that the malicious package @openclaw-ai/openclawai impersonated an OpenClaw installer and used a multi-stage chain to steal credentials and other sensitive data, while The Hacker News reported it abused npm install behavior and deployed remote-access malware. This incident is what inspired this project due to its relevancy at this moment a scanner that looks for lifecycle-hook abuse, shell execution, sensitive-path access, obfuscation, and outbound-beacon patterns is directly aimed at the same attack surface


What was Learned:



Tech Stack:
- Python
- OpenAI
- 