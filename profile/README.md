<picture>
  <source media="(prefers-color-scheme: dark)" srcset="../resources/images/cs_wide_dark_bg.png">
  <source media="(prefers-color-scheme: light)" srcset="../resources/images/cs_wide_light_bg.png">
  <img alt="Cracking Shells" src="../resources/images/cs_wide_dark_bg.png">
</picture>

# Cracking Shells — Scientific Software Access for LLM-Powered Research

**Cracking Shells** is an open-source initiative that makes scientific software accessible to Large Language Models (LLMs) through the [Model Context Protocol (MCP)](https://modelcontextprotocol.io). Our mission: empower researchers to use LLMs as scientific assistants with proper, controlled access to established tools, databases, and resources — **always with accurate citations**.

## The Ecosystem

### Hatch! 🐣

**[Hatch!](https://github.com/CrackingShells/Hatch)** is the package manager for the Cracking Shells ecosystem. It handles:

- Declaring MCP server dependencies and the citations an LLM must report when using them
- Automatic installation and isolation of Python environments for each package's dependencies
- Versioning and dependency resolution across the ecosystem

### Hatchling 🐥

**[Hatchling](https://github.com/CrackingShells/Hatchling)** is the user-facing CLI chat interface that connects local LLMs (via [Ollama](https://ollama.com)) to MCP servers. Key features:

- Interactive chat with managed access to scientific tools
- Support for local LLMs via Ollama
- Tool execution monitoring with timeout controls
- Automatic citation of all Hatch-managed MCP servers used during a session

### Scientific Domain Repositories *(Coming Soon)*

We are building a network of community-driven repositories, each housing MCP server wrappers for tools in a scientific discipline. We invite contributors from all fields to participate:

| Repository | Domain |
|---|---|
| Cracking Biology | Bioinformatics tools (BLAST, UniProt, PubMed, …) |
| Cracking Chemistry | Chemical databases, molecular visualization, reaction prediction |
| Cracking Physics | Simulation tools, data analysis, and visualization |
| Cracking Mathematics | Computer algebra systems, statistical tools, and visualization |
| Cracking Computer Science | Code analysis, execution environments, and development tools |
| Cracking Engineering | CAD integration, simulation tools, and material databases |

## Roadmap

- **Phase 1 — Core Infrastructure** *(current)*
  - Stabilize the Hatchling CLI interface
  - Establish the Hatch package architecture and schema
  - Develop versioning and dependency management

- **Phase 2 — Scientific Domain Expansion**
  - Launch Cracking Biology with essential bioinformatics tools
  - Establish contribution guidelines for scientific software integration

- **Phase 3 — Community Growth**
  - Support third-party MCP server contributions
  - Deploy scientific domain repositories
  - Develop educational resources for researchers
  - Organize dev jams and hackathons

- **Phase 4 — User Experience**
  - Graphical user interface for Hatchling
  - User-defined tool chains and workflows
  - Integration with research notebooks and documentation tools

## Contributing

The project is in its early stages. If you're interested in contributing, using our tools in your research, or have questions, please reach out:

- **Project Lead:** Eliott Jacopin
- **Email:** <eliott.jacopin@riken.jp>

## License

Hatch! and Hatchling are released under the [AGPLv3 License](https://www.gnu.org/licenses/agpl-3.0.html). Individual domain repositories may carry their own licenses based on the software they integrate with — see each repository for details.
