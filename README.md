# Claude Code Warcraft Sound Effects

A fun configuration for Claude Code that adds Warcraft-inspired sound effects to your coding workflow!

## Features

🎮 **Session Management Sounds**
- Random startup sounds when Claude starts ("ready-to-serve", "ready-to-work", "we-are-ready-master")
- Completion sounds when work is finished ("jobs-done", "work-complete", "work-completed")

🔧 **Tool-Specific Audio Feedback**
- Different system sounds for each tool (Write, Edit, MultiEdit, TodoWrite, Bash)
- Audio confirmation for every action Claude takes

💬 **Interactive Responses**
- Random sound effects when you submit prompts (including "huh-what", "i-dont-wanna-do-this", "this-way-no-that-way")

## Installation

1. Create the Claude settings directory:
```bash
mkdir -p ~/.claude/sounds
```

2. Add your Warcraft sound files to `~/.claude/sounds/`:
- `ready-to-serve.wav`
- `ready-to-work.wav` 
- `we-are-ready-master.wav`
- `more-work.wav`
- `huh-what.wav`
- `i-dont-wanna-do-this.wav`
- `this-way-no-that-way.wav`
- `jobs-done.wav`
- `work-complete.wav`
- `work-completed.wav`

3. Copy the configuration to `~/.claude/settings.json`:

## Requirements

- Linux system with `paplay` (PulseAudio)
- Claude Code CLI

## Usage

Once configured, Claude will automatically play sounds when:
- Starting a session
- You submit prompts  
- Claude uses different tools
- Work is completed

## Customization

You can easily customize this by:
- Adding your own sound files to `~/.claude/sounds/`
- Modifying the sound arrays in the configuration
- Adding hooks for other Claude Code events
- Using different audio players (replace `paplay` with your preferred player)

## Notes

- Update the paths in the configuration to match your home directory
- Soundfiles are owned by Blizzard

Enjoy your immersive coding experience! 🎮✨

