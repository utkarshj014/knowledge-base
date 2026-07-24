# Engineering Knowledge Base

This repository is my personal engineering knowledge base, made public so anyone can benefit from it. It documents my learnings and explorations as an engineer, organized to help readers learn things fundamentally and conceptually, build strong mental models, and understand systems from core concepts to advanced topics.

> [!NOTE]
> This repository is continuously updated as I learn. Articles may be revised over time to improve accuracy, clarity, or reflect better understanding.

---

## 📂 Repository Structure

```
knowledge-base/
├── .github/              # Shared assets and configuration
│   └── assets/           # Visual diagrams categorized by topic
│       ├── backend/          # Diagrams for backend & infrastructure content
│       ├── backend-systems/  # Diagrams for identifiers & system design content
│       └── security/         # Diagrams for cryptographic & security content
└── docs/                 # Categorized technical articles
    ├── backend/          # Server architecture, identifiers, and runtime mechanics
    └── security/         # Cryptography, authentication, and protocols
```

---

## 📖 Curated Articles

### 🔐 Security & Cryptography

- [Hashing & Cryptography](docs/security/hashing-and-cryptography.md) — A comprehensive explanation of deterministic hash functions, the avalanche effect, and the three pillars of cryptographic hash resistance.

### ⚙️ Backend & Infrastructure

- [Graceful Shutdown Mechanics](docs/backend/graceful-shutdown-mechanics.md) — OS-level process lifecycle, signals, server draining, the Keep-Alive trap, and the immutable four-phase shutdown sequence for production Node.js applications.
- [Unique Identifiers: UUID vs CUID](docs/backend/unique-identifiers-uuid-and-cuid.md) — UUIDv4, UUIDv7, and CUID2 compared across database performance, cryptographic security, B-Tree indexing mechanics, and the Dual-ID pattern for production architectures.

---

## 🛠️ Article Standards & Style

To ensure all documentation is clean, readable, and highly accessible, every article follows these presentation patterns:

- **Conceptual Depth**: Explains the underlying mechanics (_why_ and _how_) rather than just definitions, ensuring a solid mental model.
- **Visual Elegance**: Diagrams are centered and styled via HTML to ensure proper margins, rounded corners (`border-radius: 8px`), and a clean, responsive layout.
- **Scannability**: Key rules, mathematical formulas, and critical takeaways are highlighted using native GitHub-style callouts (`> [!IMPORTANT]`).
- **Safe Copying**: All terminal commands and bash blocks are presented prompt-free.

---

## 🌟 Support & Contribute

If you find this handbook helpful, please consider:

- **Starring** ⭐ this repository to help others discover it.
- **Following** 👥 me [utkarshj014](https://github.com/utkarshj014) on GitHub.
- **Watching** 👀 the repository to get updates on new content.
- **Contributing** 🛠️ by opening a Pull Request with fixes or additions.
- **Sharing** 📢 this project with other developers who want to learn fundamentally.
