# Installfest

- [x] [Github and Initial Setup](github.md)
- [x] [Git](git.md)
- [ ] **Bash Configuration**
- [ ] [Command Line Tools - Xcode (macOS only)](command_line_tools.md)
- [ ] [Homebrew](homebrew.md)
- [ ] [Node](node.md)
- [ ] [Ruby](ruby.md)
- [ ] [PostgreSQL](postgres.md)
- [ ] [MongoDB](mongodb.md)
- [ ] [VS Code](vscode.md)
- [ ] [Chrome](chrome.md)

## Bash Configuration (macOS only)

macOS ships with utilities that are slightly different from standard Linux tools.
To smooth out *some* of the differences, we need to change how macOS loads our
shell (`bash`) configuration. On Linux, this script will check that you are using
the correct shell.

 In your terminal, type:

```bash
  scripts/bash.sh
```

## macOS Catalina Users

If you are running macOS Catalina version, you'll receive a message in the Terminal each time you open it.  You can safely ignore it but you can also fix it as follows:

In the Terminal, type:

```bash
code .bash_profile
```

This will launch VS Code with a file called `.bash_profile` open.  Inside this file, at the very end, add the following line and then save and close the file.

```bash
export BASH_SILENCE_DEPRECATION_WARNING=1
```

Exit the Terminal completely (**Terminal** > **Quit Terminal**) and then reopen it.

[Continue With Installfest](command_line_tools.md)
