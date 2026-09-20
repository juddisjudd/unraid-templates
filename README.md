# Unraid Templates

A collection of custom Docker templates for Unraid's Community Applications.

## Available Templates

| Template | Category | Description |
|---|---|---|
| **RuneScape: DragonWilds** | `GameServers` | A Docker container for running a RuneScape: DragonWilds dedicated server. |
| **Valheim** | `GameServers` | A Docker container for running a Valheim dedicated server. |
| **Rust** | `GameServers` | A Docker container for running a Rust dedicated server. |
| **Enshrouded** | `GameServers` | A Docker container for running an Enshrouded dedicated server. |
| **Hytale** | `GameServers` | A Docker container for running a Hytale dedicated server. |
| **Crustation** | `GameServers` `Tools` | A control panel for game servers: start, stop and watch your servers from one web interface. |

## Installation / How to Use

To use these templates on your Unraid server, you can add this repository to your Docker settings.

1. Navigate to the **Docker** tab in your Unraid web interface.
2. Scroll to the bottom of the page and locate the **Template repositories** field.
3. Add the URL for this repository: `https://github.com/juddisjudd/unraid-templates` (Make sure to append it to the end of the existing list, separated by a comma or on a new line).
4. Click **Apply**.
5. Click **Add Container** at the bottom of the Docker page.
6. In the **Template** dropdown at the top, you should now see the templates from this repository available for selection.

*Alternatively, you can add the repository URL within the Community Applications settings under **Additional Repositories**.*

## Contributing

Feel free to submit an issue or pull request if you have any suggestions, improvements, or new templates you'd like to share!

## Credits

Special thanks to the original creators of the Docker images used in these templates:
- **RuneScape: DragonWilds**: Docker image provided by [indifferentbroccoli](https://github.com/indifferentbroccoli/runescape-dragonwilds-server-docker) ([Docker Hub](https://hub.docker.com/r/indifferentbroccoli/runescape-dragonwilds-server-docker)).
- **Valheim**: Docker image provided by [indifferentbroccoli](https://github.com/indifferentbroccoli/valheim-server-docker) ([Docker Hub](https://hub.docker.com/r/indifferentbroccoli/valheim-server-docker)).
- **Rust**: Docker image provided by [indifferentbroccoli](https://github.com/indifferentbroccoli/rust-server-docker) ([Docker Hub](https://hub.docker.com/r/indifferentbroccoli/rust-server-docker)).
- **Enshrouded**: Docker image provided by [indifferentbroccoli](https://github.com/indifferentbroccoli/enshrouded-server-docker) ([Docker Hub](https://hub.docker.com/r/indifferentbroccoli/enshrouded-server-docker)).
- **Hytale**: Docker image provided by [indifferentbroccoli](https://github.com/indifferentbroccoli/hytale-server-docker) ([Docker Hub](https://hub.docker.com/r/indifferentbroccoli/hytale-server-docker)).
