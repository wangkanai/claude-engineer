# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is the **claude-engineer** repository - a project focused on enhancing Claude Code with engineer orchestration and project coordination for software product development. It appears to be a minimal setup project, potentially serving as a foundation or configuration layer for Claude Code development workflows.

## Repository Structure

This is a lightweight repository containing:
- `README.md` - Basic project description
- `LICENSE` - MIT License (Copyright 2025 Sarin Na Wangkanai)
- `repomix.config.json` - Configuration for repomix tool (XML output, security checks enabled)
- `.repomixignore` - Ignore patterns for repomix (untracked)

## Development Commands

Currently, this repository does not contain traditional build scripts or package management files. The primary tool configured is:

### Repomix Usage
```bash
# Generate codebase summary with repomix
repomix

# Output will be generated as repomix-output.xml
# Configuration includes security checks and Git change sorting
```

## Key Configuration

### Repomix Configuration (`repomix.config.json`)
- **Output**: XML format with file summaries and directory structure
- **Security**: Security checks enabled
- **Git Integration**: Sorts files by recent changes (last 100 commits)
- **File Size Limit**: 52MB maximum per file
- **Token Encoding**: Uses o200k_base encoding

## Context

This repository is part of the broader Wangkanai ecosystem, which includes 16+ active projects spanning enterprise applications, .NET libraries, geospatial systems, and industry-specific solutions. This particular repository appears to serve as a foundation or orchestration layer for Claude Code integration with engineering workflows.

## Notes for Future Development

- This is a minimal setup repository with no traditional build pipeline
- Primary focus appears to be on documentation and configuration rather than executable code  
- Consider the repository as a coordination hub rather than a traditional software project
- Any development should align with the broader Wangkanai ecosystem patterns (.NET, Clean Architecture, etc.)