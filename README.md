AsyncRAT Malware Investigation | XLMRat Lab

Analyst: Oren Heskia Date: February 2026

Executive Summary
This project involved a deep-dive investigation into a multi-stage malware infection using the XLMRat lab environment from CyberDefenders. The analysis successfully reconstructed the complete attack chain, starting from initial network traffic and ending with identified command-and-control (C2) infrastructure.

Technical Highlights
  Network Forensics: Analyzed PCAP files to identify a multi-stage infection and extracted malicious payloads directly from HTTP streams.
  Script De-obfuscation: Used CyberChef and manual analysis to de-obfuscate heavily protected PowerShell scripts, revealing hidden downloader functionality.
  C2 Identification: Discovered command-and-control communication occurring on a non-standard port (TCP/222).
  Threat Intelligence: Correlated SHA256 hashes with VirusTotal to confirm the AsyncRAT malware family.
  Documentation: Produced a comprehensive 15-page incident report tailored for both technical and executive audiences.

Indicators of Compromise (IOCs)
The investigation documented 11 unique indicators, including:
  Wireshark: Network traffic and PCAP analysis.
  CyberChef: Decoding and script de-obfuscation.
  VirusTotal: Malware family correlation and hash analysis.
