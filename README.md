# MESCC Dissertation

This repository contains the dissertation materials and planning documentation for the MESCC project.

It serves as the central place for managing the dissertation, tracking its development, and maintaining supporting documentation throughout the research and implementation process.

## Repository Structure

```text
dissertation_mescc/
├── MESCCFilipeFerreiraDissertation/
│   └── Dissertation source files and related materials
├── MESCC_Dissertation_Plan/
│   └── Dissertation planning and development materials
├── .gitignore
└── README.md
```

### Dissertation

The `MESCCFilipeFerreiraDissertation/` directory contains the dissertation project, including its source files and supporting materials.

### Dissertation Plan

The `MESCC_Dissertation_Plan/` directory contains the planning documentation used to organize the dissertation work, define milestones, and track progress.

## Getting Started

Clone the repository:

```bash
git clone https://github.com/filipeisep95/dissertation_mescc.git
cd dissertation_mescc
```

Explore the directories to locate the dissertation source files and planning documentation.

### Working with the Dissertation

The tools and commands required to build the dissertation depend on the source format and configuration used by the project.

If the dissertation uses LaTeX, a typical environment includes:

- A LaTeX distribution, such as TeX Live.
- `latexmk` for automating compilation.
- A compatible LaTeX editor or text editor.

For a LaTeX project with a `main.tex` entry point, compilation can typically be performed with:

```bash
latexmk -pdf main.tex
```

Run this command from the directory containing `main.tex`. Refer to the project's configuration and source files for any additional build requirements.

## Project Goals

This repository is intended to:

- Maintain the dissertation source code and documentation under version control.
- Keep dissertation planning materials organized.
- Support incremental development and revision of the dissertation.
- Preserve the relationship between the research work, its implementation, and the final dissertation.

## Development Workflow

A typical workflow consists of:

1. Review the dissertation plan and current milestones.
2. Develop or update the dissertation content and supporting materials.
3. Compile the dissertation, when applicable, to validate the output.
4. Review the generated document for correctness and formatting.
5. Commit and push changes to the repository.

## Contributing

This repository is primarily intended to support the dissertation work.

Changes should preserve the consistency of the dissertation source files and planning documentation.

## Author

**Filipe Ferreira**

## Repository

[GitHub — dissertation_mescc](https://github.com/filipeisep95/dissertation_mescc)
