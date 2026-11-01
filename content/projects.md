---
title: Projects
---

# Projects

## Reproducible QMK Firmware Build for Keyball44 (Nix Flake)

A fork of the open-source Keyball split trackball keyboard, extended with a Nix
flake that builds the QMK firmware reproducibly with a single command, including
a dev shell for flashing and keymap development.

Based on [Yowkees/keyball](https://github.com/Yowkees/keyball)

Tech: C / Nix (Flake) / QMK Firmware

[Repository](https://github.com/lillian0x/keyball)

## Kubernetes manifest

Personal homelab configration files.

Tech: Kubernetes / Fluxcd / Nix (Flake) / pre-commit / Renovate

[Repository](https://github.com/lillian0x/voluspa)

## RSA & SHA-256 from Scratch in Python

A from-scratch implementation of RSA public-key encryption and the SHA-256 hash
function in pure Python, with no cryptography libraries. The SHA-256 output is
verified against hashlib. Built as an interactive Google Colab notebook.

Tech: Python / Google Colab / Mermaid

[Repository](https://github.com/lillian0x/rsa-and-sha256-written-in-python)

## OMUCT Navi

A campus navigation web app built by our team as an exhibit for our school festival. Visitors scanned a QR code on a flyer at the exhibition booth, searched for classrooms and facilities on their phones, and saw the route from their start point to their destination drawn on an interactive floor-by-floor map. It includes a step-free mode that avoids stairs.

My role: I was mainly responsible for the route-finding engine. I implemented the A* search and the graph construction over the campus’s indoor nodes and edges, including the step-free option that excludes stair edges, and wrote its unit tests.

Tech: Typescript / A* / pre-commit / Nix (Flake) / Mermaid / Bun / Cloudflare Worker

[Repository](https://github.com/u0021u004Du0053/omuct-navi)
