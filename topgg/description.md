<div align="center">

<img src="https://raw.githubusercontent.com/fenrai-ai/assets/main/topgg/banner.png" width="100%" alt="Fenrai">

### Discord moderation you draw as a flow, not as a settings page you hope covers your case.

You wire the rule yourself: a trigger, the conditions that have to hold, and what happens next. Tickets, levels, verification, community health and stream alerts run from the same dashboard.

<a href="https://discord.com/oauth2/authorize?client_id=YOUR_CLIENT_ID"><img src="https://img.shields.io/badge/Add%20to%20Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white&labelColor=5865F2" alt="Invite"></a>
<a href="https://www.fenrai.app"><img src="https://img.shields.io/badge/Dashboard-8B5CF6?style=for-the-badge&labelColor=1E1A29" alt="Dashboard"></a>
<a href="https://www.fenrai.app/docs"><img src="https://img.shields.io/badge/Docs-A78BFA?style=for-the-badge&labelColor=1E1A29" alt="Docs"></a>
<a href="https://dsc.gg/fenrai"><img src="https://img.shields.io/badge/Support-C084FC?style=for-the-badge&labelColor=1E1A29" alt="Support"></a>

</div>

<br>

# 🛡️ The rule builder

Drag blocks onto a canvas and connect them. **When** something happens, **if** the conditions hold, **then** the bot acts. Two blocks sit in between when you want them: **Judge**, an AI check that scores the message, and **Ask**, which pauses everything until a moderator approves.

<div align="center">
<img src="https://raw.githubusercontent.com/fenrai-ai/assets/main/topgg/rule-builder.png" width="80%" alt="The rule builder">
</div>

**Triggers** on message, on message edit, on member join, on member leave, on level up

**Conditions** message content, links, invites, images, attachments, mention count, caps, username, roles, account age, time since joining, warnings, level, recent messages, recent channels, duplicates, recent joins and leaves across the server, raid mode, channel

**Actions** delete message, purge recent messages, warn, mute, kick, ban, add role, remove role, DM, log only, lock channels, set slowmode, raise verification level, pause invites, enter raid mode

Every branch is yours: the false side can stop, or carry on into another check. Hit **Test** and the canvas replays the rule against recent messages before it ever touches a member.

<br>

# 📋 What the bot did, and why

Every action posts the rule that fired, what it did, who it hit and the message that set it off. Noisy action types can be sent to the dashboard only, so your log channel keeps just the things a moderator should react to.

<div align="center">
<img src="https://raw.githubusercontent.com/fenrai-ai/assets/main/topgg/mod-log.png" width="100%" alt="A moderation action in the log channel">
</div>

<br>

# 🧩 Twelve modules, one dashboard

<div align="center">
<img src="https://raw.githubusercontent.com/fenrai-ai/assets/main/topgg/modules.png" width="100%" alt="Modules">
</div>

| Module | What it does |
| :--- | :--- |
| 🛡️ **Auto-Moderation** | The flow rules above, with a review queue for anything a rule hands to a human |
| 🧹 **Manage Messages** | Purge from the dashboard or with `/purge`, filtered by author, text, bots or regex |
| ✅ **Verification** | A button or a quiz new members have to get past before they can talk |
| 🎫 **Tickets** | Members open a ticket from a panel, and the conversation is archived when it closes |
| 📈 **Levels** | XP for talking, with a configurable range and cooldown, role rewards, `/rank` and `/leaderboard` |
| 💜 **Community health** | Members, messages, joins and leaves, channel activity, retention cohorts, an activity heatmap |
| 🔴 **Stream Alerts** | Twitch, YouTube and Kick go-live posts with a role mention and your own template |
| 🔁 **Role Persistence** | Roles come back when a member rejoins |
| 📣 **Auto Publisher** | Announcement channel posts published for you |
| 🕒 **Timezone Nickname** | A member's local time kept in their nickname |
| 🤖 **AI assistant** | Ask for a setting in plain English and it changes it |
| ⚙️ **Server Setup** | Log channels, review channel, DM on warn, and what each action type logs where |

<br>

# 🖥️ The dashboard

<div align="center">
<img src="https://raw.githubusercontent.com/fenrai-ai/assets/main/topgg/dashboard.png" width="100%" alt="Dashboard">
</div>

Every module is configured on the web, and the overview answers the question you actually have: is the server growing, who is talking, and what has the bot been doing about it.

<br>

# 🤖 AI where it helps, gone where it does not

**AI checks inside a rule.** The Judge block scores a message against a question you write, on its own or with the member's recent messages for context, and you pick the score it acts on. Run out of credits and the check takes its false branch: the rest of the rule still runs.

**An assistant that changes settings.** Describe what you want and it configures the module instead of pointing you at the toggle.

Both spend from one credit meter that comes with your plan. Nothing separate to buy.

<br>

# ⌨️ Commands

`/ban` &nbsp; `/kick` &nbsp; `/mute` &nbsp; `/purge` &nbsp; `/rank` &nbsp; `/leaderboard` &nbsp; `/timezone` &nbsp; `/ping`

Short on purpose. Everything else is configured on the dashboard, where you can see what you are changing.

<br>

# 💎 Plans

| | Free | Standard | Pro |
| :--- | :---: | :---: | :---: |
| Rule builder, tickets, levels, verification, purge, logs | ✅ | ✅ | ✅ |
| Stream alerts | 3 | 10 | Unlimited |
| Moderation rules | Limited | More | Most |
| History and analytics retention | Short | Longer | Longest |
| AI checks and AI assistant | ❌ | ✅ | ✅ |

Exact numbers at **[fenrai.app/pricing](https://www.fenrai.app/pricing)**.

<br>

<div align="center">

## Add it, open the dashboard, wire your first rule

**[➕ Add Fenrai](https://discord.com/oauth2/authorize?client_id=YOUR_CLIENT_ID)** &nbsp;•&nbsp; **[🖥️ Dashboard](https://www.fenrai.app)** &nbsp;•&nbsp; **[📚 Docs](https://www.fenrai.app/docs)** &nbsp;•&nbsp; **[💬 Support](https://dsc.gg/fenrai)**

</div>
