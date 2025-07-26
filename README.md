
<p align="center">
  <img src="https://okmu.eu/dc-logo.png" alt="MuOnline Bot Logo" width="150" height="150">
</p>

<h1 align="center">MuOnline Discord Bot</h1>

<p align="center">
  A private Discord bot for MuOnline server management and player ranking.
  <br><br>
  <strong>🔔 All updates and announcements can be followed in our Discord server.</strong>
  <br>
  <a href="https://discord.gg/YGg86vZXaB"><strong>Join the Update Server</strong></a>
  <br><br>
  <a href="https://discord.com/oauth2/authorize?client_id=679785808504553476"><strong>➕ Invite the Bot</strong></a>
  &nbsp;&nbsp;&nbsp;
  <a href="#features">📌 Features</a>
  &nbsp;&nbsp;&nbsp;
  <a href="#commands">💬 Commands</a>
</p>

---

# MuOnline Discord Bot

**MuOnline Bot** is a private Discord bot designed for server administration and protection against unwanted advertisements. It also supports player ranking management and other useful features tailored for MuOnline servers.

## ⚙️ Features

- **Anti-Advertisement System** – Automatically detects and removes messages containing forbidden links.
- **Whitelist** – Allows trusted domains to bypass the ad filter.
- **Ranking System** – Supports configuration and display of player ranking tables.
- **SQL Configuration** – Set up MSSQL database connection parameters.
- **Log Channel** – Set a channel to log deleted messages.
- **Slash Commands** – Modern `/` command support for easier control.

## 🔐 Usage

This bot is **private** and not publicly available. It is self-hosted and used only on selected servers.

---

# 📘 MuOnline Bot Command Reference

MuOnline Bot supports various `/` commands to manage your server, handle player rankings, and configure settings.

## 📜 Commands

### `/addwhitelist`

**Description:** Adds a domain to the whitelist so it won’t be blocked by the anti-ad system.

**Usage:**
```
/addwhitelist domain:<domain>
```
- `domain`: The domain you want to whitelist (e.g., `example.com`)

---

### `/setlogchannel`

**Description:** Sets the channel where deleted message logs will be posted.

**Usage:**
```
/setlogchannel channel:<#channel>
```
- `channel`: The Discord channel to use for logging (e.g., `#logs`)

---

### `/rankings`

**Description:** Displays player rankings using the configured table and columns.

**Usage:**
```
/rankings
```
- No additional parameters required.

---

### `/serversql`

**Description:** Sets MSSQL database connection parameters.

**Usage:**
```
/serversql host:<host> user:<user> password:<password> database:<database> port:<port?>
```
- `host`: MSSQL server address  
- `user`: MSSQL username  
- `password`: MSSQL password  
- `database`: MSSQL database name  
- `port` (optional): MSSQL port (default: `1433`)

---

### `/setrankings`

**Description:** Sets the table and columns used for player rankings.

**Usage:**
```
/setrankings table:<table> levelcolumn:<level> resetcolumn:<reset> grandresetcolumn:<grandreset>
```
- `table`: Table name (e.g., `Character`)  
- `levelcolumn`: Column storing player levels (e,g., `cLevel`)
- `resetcolumn`: Column storing resets  (e,g., `ResetCount`)
- `grandresetcolumn`: Column storing grand resets (e,g., `MasterResetCount`)

---

### `/antiad`

**Description:** Enables or disables the anti-advertisement feature.

**Usage:**
```
/antiad state:<on|off>
```
- `state`: Use `on` to enable or `off` to disable

---

## 🔒 Permissions

All commands require **administrator permissions**.  
If you experience issues, check your server’s configuration or contact the bot developer in discord server.

---

## 📩 Contact

For more information or support, please contact the bot developer directly.

---

## 📄 License

This project is **private** and not intended for public or commercial use.


---

## 🔗 Invite the Bot

You can add this bot to your own Discord server using the following link:

👉 [Click here to invite](https://discord.com/oauth2/authorize?client_id=679785808504553476)
