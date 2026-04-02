# Open Saw

<p align="center">
  <strong>🌲 A professional, memory-safe, and incredibly fast local coding agent CLI, carefully crafted by fivesaw. 🌲</strong>
</p>

## Overview

Open Saw is an open-source alternative for your AI development needs, providing a beautiful "green forest" themed terminal interface and lightning-fast local execution directly in your Rust and Python workspaces. Open Saw provides a robust and gorgeous workflow to generate code, run prompt files, and coordinate complex tasks from the command line, all while retaining full backward compatibility with any of your standard LLM API keys. 

## Features
- **Extremely Fast Execution**: Written entirely in secure Rust.
- **Agentic Automation**: Let the AI automatically coordinate complex coding flows across multiple files.
- **Beautiful Interface**: Minimalistic "green forest" style with an immersive developer experience.
- **Open Configuration**: Easily bring your own API keys. Supports a variety of standard configurations. 

## Getting Started

### Using the Pre-built Windows App (EXE)

To start using Open Saw immediately without installing code tools yourself:

1. Look in the **Releases** section on the right side of this repository.
2. Download the latest `saw.exe`.
3. Open a Command Prompt or PowerShell window in the folder where you downloaded `saw.exe`.
4. Run:
   ```cmd
   saw.exe
   ```
5. Follow the interactive instructions to set up your chosen API key! Or type `saw.exe --help` to see all available flags and options.

### Building from Source

If you prefer to compile it yourself:

1. Make sure you have the latest Rust toolchain installed.
2. Clone the repository and navigate to the `rust/` directory.
3. Build the release binary:
   ```bash
   cd rust
   cargo build --release
   ```
4. Find the executable at `target/release/saw`.

## Commands Reference

The command palette is fully interactive. Once in the REPL, type `/help` for an extended guide.

- `saw` - Starts the interactive REPL coding session.
- `saw "Summarize this repo"` - Runs a single explicit shot to prompt.
- `saw --version` - Print out your current binary version block.

## License

MIT License. Do your best and build the future with Open Saw!
