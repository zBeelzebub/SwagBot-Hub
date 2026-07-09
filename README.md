# SwagBot Hub

SwagBot Hub is a Roblox AI chatbot script with a polished in-game UI, fully customizable chat behavior, proximity controls, moderation tools, follow automation, local configs, and a free key system.

The public release is distributed as an obfuscated script. Users only need the loadstring below.

## Loadstring

```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/zBeelzebub/SwagBot-Hub/main/dist/SwagBotHub.lua"))()
```

## Official Discord

Join the official SwagBot Hub Discord for support, updates, and announcements:

https://discord.gg/tK2WfXSfE9

The script also copies the official Discord invite to your clipboard when it launches.

## Key System

SwagBot Hub is free to use, but it uses a Work.ink key system to support development.

When you run the script:

1. Execute the loadstring.
2. If you do not have a valid saved key, the key screen will appear.
3. Click `Get Key`.
4. Complete the Work.ink steps.
5. Copy the generated key.
6. Paste the key into SwagBot Hub.
7. Click `Verify`.

Valid keys are saved locally, so you usually do not need to repeat the key process until your key expires.

## Features

- Modern dark UI built for SwagBot Hub.
- Always-visible SwagBot Hub branding.
- UI toggle key: `P`.
- Bottom-right notifications.
- Configurable AI provider and model settings.
- Personality presets and custom system prompts.
- Optional per-user memory so conversations stay separated.
- Auto-reply controls for Roblox chat.
- Proximity filtering and selective player mode.
- Moderation tools for blocking and timing out users.
- Follow automation with pathfinding and direct movement modes.
- Local config saving and loading.
- Work.ink key flow with server-side verification.

## Basic Usage

1. Run the loadstring.
2. Complete the key system if prompted.
3. Open the `General` tab.
4. Choose your AI settings.
5. Enable `Auto Reply`.
6. Adjust behavior, perception, moderation, and config options as needed.

## Controls

| Action | Control |
| --- | --- |
| Toggle UI | `P` |
| Get a key | Click `Get Key` on the key screen |
| Verify a key | Paste the key and click `Verify` |
| Save settings | Use the `Configs` tab |
| Load settings | Use the `Configs` tab |

## Configs

Configs are saved locally by your executor. Other users do not receive your saved configs.

Each user has their own local config files, so everyone starts with the default script settings unless they save their own config.

## Requirements

You need a Roblox executor with support for common executor APIs, including:

- HTTP requests such as `request`, `http_request`, or `syn.request`.
- Clipboard access such as `setclipboard`.
- File functions such as `writefile`, `readfile`, `isfile`, `makefolder`, and `listfiles` for saved configs.

Feature support may vary depending on your executor.

## Troubleshooting

If the UI does not open, try rejoining the game and executing the loadstring again.

If the key screen keeps appearing, your saved key may have expired or your executor may not support local file saving.

If AI replies are not working, check your provider/model settings and make sure HTTP requests are supported by your executor.

For help, join the official Discord:

https://discord.gg/tK2WfXSfE9

## Disclaimer

SwagBot Hub is provided as-is. Use it responsibly and at your own risk.

Using executors, automation, or third-party scripts may violate Roblox's Terms of Service. You are responsible for how you use the script.

Some AI providers may require your own API key and may charge for usage.

## License

See [LICENSE](LICENSE) for license terms.
