# AI Agent Developer Setup - jeneya-cabildo

## Developer Information
- **Name:** jeneya-cabildo
- **Workshop Cohort:** Bootcamp Cohort
- **Program:** AI Agent Developer 10-Week Bootcamp
- **Submission Date:** Week 1 - Setup Verification

---

## Development Environment Checklist

### ✅ Node.js Installed
Node.js is installed and ready for development.
<img src="ECA NODE.png" alt="node">

---

### ✅ Git Installed
Git version control system is properly installed.

<img src="ECA GIT.png" alt="git">

**Screenshot:** [Git version screenshot - can be taken with `git --version` in terminal]

---

### ✅ VS Code Insider with GitHub Copilot Enabled
VS Code Insider is running with GitHub Copilot extension active and connected.

**Features:**
- VS Code Insider for latest features
- GitHub Copilot extension enabled
- Full IntelliSense and code completion
- AI-powered code suggestions and explanations

<img src="ECA VISUAL.png" alt="visual">

### ✅ Claude Desktop with 4 MCP Servers Connected
Claude Desktop is configured with all required MCP servers for enhanced AI capabilities.

**Screenshot:** [Add screenshot of Claude Desktop showing all 4 MCP servers]

---

## MCP Servers Overview

### 1. **Rolldice MCP Server**
**Purpose:** Dice rolling utility for randomization and probabilistic scenarios
- **Functionality:** Generates random dice rolls with configurable faces
- **Use Cases:** Game development, randomization testing, probability demonstrations
- **Status:** ✅ Connected

### 2. **Bootcamp AI Agent MCP Server**
**Purpose:** Custom AI Agent for bootcamp-specific tasks and guidance
- **Functionality:** Provides bootcamp curriculum integration, progress tracking, and AI-enhanced learning
- **Use Cases:** Learning support, task verification, bootcamp workflow optimization
- **Status:** ✅ Connected

### 3. **Calendar Booking MCP Server**
**Purpose:** Scheduling and calendar management integration
- **Functionality:** Creates, manages, and queries calendar events and bookings
- **Use Cases:** Schedule management, meeting coordination, time slot booking
- **Status:** ✅ Connected

### 4. **GitHub MCP Server**
**Purpose:** GitHub repository interaction and version control operations
- **Functionality:** Enables reading/writing to GitHub repos, managing issues, creating PRs, committing code
- **Use Cases:** Repository management, collaborative development, automated workflows
- **Status:** ✅ Connected

---

## Troubleshooting Notes

### Issue 1: MCP Server Connection Failures
**Problem:** One or more MCP servers not connecting in Claude Desktop
**Solution:**
- Verify Claude Desktop configuration file path: `%AppData%\Claude\claude_desktop_config.json`
- Ensure all server endpoints are running and accessible
- Check that Node.js processes are not blocked by firewall
- Restart Claude Desktop application

### Issue 2: GitHub MCP Server Authentication
**Problem:** GitHub MCP server unable to authenticate
**Solution:**
- Generate a personal access token at https://github.com/settings/tokens
- Set `GITHUB_TOKEN` environment variable
- Ensure token has necessary scopes (repo, read:user, etc.)
- Restart Claude Desktop to load new environment variables

### Issue 3: Port Conflicts
**Problem:** MCP servers failing to start due to port conflicts
**Solution:**
- Identify which process is using the port: `netstat -ano | findstr :[port]`
- Kill the conflicting process or configure MCP server to use different port
- Update `claude_desktop_config.json` with new port configuration

### Issue 4: VS Code Copilot Authentication
**Problem:** GitHub Copilot not working in VS Code Insider
**Solution:**
- Sign in to GitHub account through VS Code
- Install latest GitHub Copilot extension
- Check that your GitHub account has active Copilot subscription
- Reload VS Code window

---

## Development Environment Configuration

### System Information
- **OS:** Windows
- **Terminal:** PowerShell 5.1+
- **Git:** v2.53.0 (Windows)
- **Node.js:** v20.x or higher
- **VS Code:** Latest Insider Build
- **Claude Desktop:** Latest version

### Key Technologies
- **Next.js** - React framework for production
- **TypeScript** - Type-safe JavaScript development
- **Tailwind CSS** - Utility-first CSS framework
- **React** - UI library
- **MCP Protocol** - Model Context Protocol for AI integration

---

## Next Steps

1. ✅ Verify all MCP servers are connected
2. ✅ Test GitHub MCP server with repository operations
3. ✅ Create meaningful commits demonstrating version control workflow
4. ✅ Document any additional insights from the setup process
5. ✅ Continue with bootcamp curriculum

---

## Contact & Support
For issues or questions about this setup, refer to:
- Official MCP Documentation
- Claude Desktop Help
- VS Code Insider Documentation
- GitHub MCP Server Repository

---

*Last Updated: March 17, 2026*
