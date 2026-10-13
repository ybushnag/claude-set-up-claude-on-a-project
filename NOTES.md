# Claude Code Setup Notes

## Project Overview
This project is a Node.js Express API used for Claude Code training.

## CLAUDE.md
I created a project-level CLAUDE.md file to provide Claude with clear instructions about the project, available commands, and working rules.

## Permission Settings
I configured permissions in .claude/settings.json:

- **Allow:** Running tests and lint checks.
- **Ask:** Installing dependencies and starting the application.
- **Deny:** Reading sensitive environment files and running a dangerous recursive deletion command.

## Safety and Workflow
Claude should review existing files, explain proposed changes, and request approval before modifying application code.

## Goal
Make Claude Code useful and safe when working on this project without changing the existing application code.