# Privacy-Preserving AI Orchestration Framework for SOC Automation

SLIIT ISP Group 32.

This public repository publishes the project's file/folder architecture only (structure, not the working source code, which stays in the team's private repository). Layout:

- services/sanitizer - PII/secret sanitization layer
- services/llm-inference - Ollama-backed LLM analysis + RAG
- services/enrichment - CVE/EPSS/KEV + MISP threat intel enrichment
- services/reporting - SysReptor report generation
- services/dashboard - analyst web portal
- integrations/wazuh - Wazuh SIEM alert ingestion
- n8n - orchestration workflow definition
- infra/proxmox-lab - virtualization lab docs
- evaluation - test data and scripts
