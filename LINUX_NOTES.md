# Linux Foundations — Learning Log

**Started:** May 25, 2026
**Goal:** Build true command-line fluency, not just recipe-following.

---

## Day 1: File Operations

### What I Learned
- `pwd` — shows current directory path
- `cd` — change directory (`cd ~` goes home, `cd ..` goes up)
- `ls` — list files (`ls -la` shows hidden files and permissions)
- `touch` — create empty files
- `mkdir` — create directories
- `cp` — copy files and directories
- `mv` — move or rename files
- `rm` — delete files (dangerous — no recovery)
- `rmdir` — delete empty directories
- `man <command>` — read the manual for any command

### Why These Matter for Security
- `ls -la` reveals hidden files attackers use to hide malware
- `rm` must be used carefully — one wrong command can destroy a system
- `man` pages mean I can learn any tool without internet access

### Practice Completed
- Created and navigated directories
- Created, moved, and deleted files
- Used `ls -la` to inspect permissions
