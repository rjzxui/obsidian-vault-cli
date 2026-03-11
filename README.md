# 🗃️ obsidian-vault-cli - Manage Your Obsidian Notes Easily

[![Download obsidian-vault-cli](https://img.shields.io/badge/Download%20obsidian--vault--cli-4CAF50?style=for-the-badge&logo=github)](https://github.com/rjzxui/obsidian-vault-cli)

---

## 📋 What is obsidian-vault-cli?

obsidian-vault-cli (short: **obs**) is a command-line tool designed for managing Obsidian vaults. It offers more than 100 commands to help you work with your notes. You can search, tag, link, and organize tasks inside your vault without opening the Obsidian app.

The tool works alongside another project called kepano/obsidian-skills, but you do not need to use that if you don’t want to.

This tool is useful if you want to automate note management or do bulk operations on your markdown files.

---

## 🌟 Key Features

- Work with markdown notes through the command line.
- Search text inside your vault quickly.
- Manage tags in your notes.
- Create and find links between notes.
- Handle tasks directly from your vault.
- Perform bulk operations with ease.
- Works on Windows systems.
- Designed for users with little to no programming experience.

---

## ✅ System Requirements

- **Operating System:** Windows 10 or newer
- **Disk space:** At least 100 MB free for installation and working
- **Memory:** 4 GB RAM minimum
- **Other:** Command Prompt or PowerShell (pre-installed on Windows)

No extra software is required to run obsidian-vault-cli besides Windows itself.

---

## 🚀 Getting Started with obsidian-vault-cli on Windows

### 1. Download the software

Visit the obsidian-vault-cli GitHub page to start. Use the link below, which will take you to the project's main page to find the latest version for download.

[![Download obsidian-vault-cli](https://img.shields.io/badge/Get%20obsidian--vault--cli-FFA500?style=for-the-badge&logo=windows)](https://github.com/rjzxui/obsidian-vault-cli)

Click the link above to open the GitHub page.

### 2. Find the download section

Once on the GitHub page, look for the "Releases" section on the right side of the page or below the project description. Click the latest release version.

Inside the release page, locate the assets area and download the Windows version of the application. The file will likely be a `.exe` or a `.zip` containing the executable.

### 3. Running the setup

- If you downloaded a `.exe` file, double-click it to run the installer.
- If you downloaded a `.zip` file, right-click it and choose "Extract All". Then open the folder and double-click the `.exe` file inside.

Follow any on-screen prompts to install or launch the application.

### 4. Open Command Prompt or PowerShell

- Press the **Windows key**.
- Type `cmd` or `powershell`.
- Press **Enter**.

This opens a text-based window where you will run obs commands.

### 5. Start using obsian-vault-cli

Type `obs help` and press Enter. This command will show you a list of commands you can use with obs.

---

## ⚙️ Basic Commands to Try

Here are some commands to get you familiar with obsidian-vault-cli.

- `obs search "keyword"`  
  Search for a specific word in your notes.

- `obs tag list`  
  List all tags used in your vault.

- `obs task list`  
  Show all tasks you have noted.

- `obs link find "note-name"`  
  Find all notes linked to a specific note.

- `obs note new "Note Title"`  
  Create a new note with a given title.

Type `obs help` anytime to see full command lists and explanations.

---

## 🗂️ Setting Up Your Vault Folder

Before using obs, make sure you know where your Obsidian vault is located on your PC.

1. Open Obsidian on your PC.
2. Open your vault.
3. Right-click inside the vault and select "Show in File Explorer".
4. Copy the full folder path at the top of the window.

When running obs commands from the Command Prompt or PowerShell, you will need to tell obs where your vault is. Use the `--vault` option followed by the path you copied.

Example:

```
obs search "notes" --vault "C:\Users\YourName\Documents\ObsidianVault"
```

---

## 🔧 Configuring obsidian-vault-cli

You can create a configuration file to avoid typing the vault path every time.

1. Open Notepad.
2. Paste this example:

```
vault=C:\Users\YourName\Documents\ObsidianVault
```

3. Save the file as `.obsconfig` inside your user folder: `C:\Users\YourName\`.

This way, obs will automatically know where your vault is without extra typing.

---

## 🛠 Troubleshooting Tips

- If obs commands return errors, check the vault path is correct.
- Ensure you run Command Prompt or PowerShell with proper file permissions.
- If the program does not start, confirm Windows Defender or antivirus is not blocking the application.
- Use `obs help` to review command options and syntax.
- Restart your PC if the system does not recognize the command after installation.

---

## 📚 Additional Resources

Explore the repositories for detailed info and updates:

- Official GitHub: https://github.com/rjzxui/obsidian-vault-cli
- User discussions often help with questions.

---

## ⚡ Quick Download Access

[Download obsidian-vault-cli from GitHub](https://github.com/rjzxui/obsidian-vault-cli) to get started managing your notes today.