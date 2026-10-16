# CS54 Data Communication and Networking — CIE-1

Two documents, meant to be read in this order:

1. **`DCN_Ground_Zero.pdf`** — 16-page prerequisites booklet. Every concept the Strike Sheet assumes you already have, built from nothing: the layered model, encapsulation, the four addresses, the binary and bitwise maths behind all Unit 3 numericals, sockets, delays, RTT, TCP vs UDP, and how reliability is actually constructed. Ends with a 12-step walkthrough of one web request that touches all three units, plus an acronym decoder and a glossary.
2. **`DCN_CIE1_Strike_Sheet.pdf`** — 34-page revision sheet for Internal Test 1.

## Scope
- **Unit 1** complete — Section A (data communication, networks, network types, protocol layering, OSI and TCP/IP models) and Section B (HTTP, FTP, SMTP/email, DNS, P2P).
- **Unit 2** complete — multiplexing/demultiplexing, UDP, Go-Back-N, Selective Repeat, TCP (segment structure, RTT estimation, reliable data transfer, flow control, connection management, congestion control).
- **Unit 3** up to **IPv4 addressing** — network layer role, IPv4 address and notations, prefix/suffix, classful, classless (CIDR), mask/first/last address, block allocation, subnetting.

Routing algorithms, Unit 4 and Unit 5 are out of scope.

## Contents
- Paper-pattern breakdown and a topic-frequency table built from 8 past papers (76 questions): CIE-1 Apr 2025, CIE-1 May 2024, CIE-1 Jun 2023, CIE-1 Jun 2021, CIE-2 Jul 2024, SEE Jan 2020, Makeup Feb 2020, SEE Feb 2024.
- 27 high-probability questions with exam-ready answers sized to 5 marks, each with diagrams, tables, memory hooks and a scoring key.
- Mnemonic vault and a formula/number card for last-minute revision.

## Rebuilding the PDFs
Sources are in `src/` — self-contained HTML with inline SVG diagrams, no external assets. Render either with headless Chromium:

```
chromium --headless --print-to-pdf=DCN_CIE1_Strike_Sheet.pdf \
         --no-pdf-header-footer src/DCN_CIE1_Strike_Sheet.html
```
