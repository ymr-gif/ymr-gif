<h1 align="center">Yamier Zane</h1>

<p align="center">
  Grade 12 student in Iloilo, Philippines. I build and self-host what I use: an AI memory
  platform, an NFC-and-face attendance system, and a WebGL deck that carried its research defense.
</p>

<p align="center">
  <a href="https://eidetic.work">Live demo: eidetic.work</a> ·
  <a href="https://github.com/ymr-gif?tab=repositories">All repos</a> ·
  <a href="mailto:cabucosyamierzane@gmail.com">Email</a>
</p>

---

## Projects

### [Eidetic](https://github.com/ymr-gif/eidetic)

Self-hosted AI memory platform. Multi-user chat with multi-model routing, hybrid RAG,
persistent graph memory and an agent tool loop, in one Docker Compose stack. Google Drive,
Calendar and Gmail connectors are built but switched off in the public demo. Every demo
login gets a private, auto-expiring sandbox with a hard spend cap.

- Try it: [eidetic.work](https://eidetic.work), login `demo` / `eidetic-demo`. It runs on a home server, so it is sometimes offline.
- Python, FastAPI, React, Postgres + pgvector, Redis, Neo4j

### [Dual-Factor Attendance System](https://github.com/ymr-gif/Dual-Factor-Attendance-System)

An NFC card identifies the student and a face check confirms it is really them, to catch
cloned and shared cards. A continuous perception pipeline correlates taps with faces in real
time, with passive liveness, an operator dashboard, and a one-command installer for Debian
and macOS. Research prototype: see its README on biometric data handling before using it.

- Python, FastAPI, TypeScript, Postgres + pgvector, Arduino + RC522

### [S.A.F.E. Defense Deck](https://github.com/ymr-gif/dual-factor-attendance-defense)

The research proposal defense for the attendance system, built as a web presentation
instead of slides: 3D model deconstruction, scripted animation beats, keyboard-driven.

- Watch it: [ymr-gif.github.io/dual-factor-attendance-defense](https://ymr-gif.github.io/dual-factor-attendance-defense/)
- anime.js v4, Three.js

---

## Contact

[cabucosyamierzane@gmail.com](mailto:cabucosyamierzane@gmail.com)
