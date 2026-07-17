# MossDeath

Dying should be a setback, not a scavenger hunt through a pile of despawning items. MossDeath saves a player's drops in a protected death chest and gives them a clear way to find and recover everything.

## The player experience

- Items are stored safely in a chest or custom player-head marker
- Right-clicking opens the saved inventory; configured interactions can also drop its contents
- Holograms, particles and expiry timers make the chest easy to understand
- Private messages include the chest location and remaining time
- Java players can receive a clickable teleport prompt, with a Bedrock-friendly command prompt for Geyser players
- Inventory size can stay fixed or grow to fit the saved contents

Server owners can control expiration, permanent chests, explosion protection, blocked worlds and whether expired contents are dropped. Access rules range from owner-only to Towny town, nation, alliance or friend access. It also respects common protection plugins such as WorldGuard, GriefPrevention and PlotSquared.

MossDeath includes PlaceholderAPI support and lifecycle events so other plugins can safely react before a chest spawns, after it spawns or when it is destroyed.

## Source availability

This is a private production plugin. The repository exists to present the project; its source code and live server configuration are not public.
