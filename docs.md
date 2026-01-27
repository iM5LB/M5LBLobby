# M5LB Lobby Documentationssssssssss

<!-- 
Image Usage Examples:

1. Using **Image**: syntax:
**Image**: https://your-domain.com/image.png

2. Using markdown syntax:
![Alt text](https://your-domain.com/image.gif)

3. Images work with:
- PNG files
- JPG/JPEG files  
- GIF files (animated)
- WebP files
- Any web-accessible image URL

4. Best practices:
- Use descriptive alt text
- Keep images under 2MB for fast loading
- Use HTTPS URLs
- Consider using a CDN for better performance
-->

## getting-started
- **Name**: Getting Started
- **Icon**: `fa-rocket`
- **Color**: `text-green-400`
- **Background**: `bg-green-500/10`
- **Border**: `border-green-500/30`
- **Description**: Welcome to M5LB Lobby! Here's everything you need to start.

### Server Connection
- Java Edition: 1.8 - 1.21+
- Bedrock: Mobile, Console, Win10

### First Steps
- `/discord link` - Link Discord account
- `/rg create <name>` - Claim your land
- `/bal` - Check balance
- `/sethome` - Save location

### Getting Started Guide
**Image**: https://cdn.modrinth.com/data/5RyYvL8C/images/a1244aaf472b1276888f99278b0e4da431bf892c.gif
**Tip**: Follow these steps to get started on the server! You can use **bold text**, *italic text*, `inline code`, and [links](https://example.com) in tips and notes.

### Markdown Formatting Examples
- **Bold text**: Use `**bold**` or `__bold__`
- *Italic text*: Use `*italic*` or `_italic_`
- `Inline code`: Use backticks
- [Links](https://github.com): Use `[text](url)` format
- ~~Strikethrough~~: Use `~~text~~`

### Code Examples
- `/help` - Shows **all** available commands with *detailed* descriptions
- `/spawn` - Teleports you to the main spawn area
- `/home [name]` - Go to your saved home location

### Advanced Features
**Note**: You can now use full markdown in notes! This includes **bold**, *italic*, `code`, [links](https://example.com), and more formatting options.

### Image Test HTML
<img width="390" height="321" alt="HTML Image Test" src="https://github.com/user-attachments/assets/8744a9be-ec12-411d-9592-b92e7772695d" />

---

## economy
- **Name**: Economy
- **Icon**: `fa-coins`
- **Color**: `text-yellow-400`
- **Background**: `bg-yellow-500/10`
- **Border**: `border-yellow-500/30`
- **Description**: Dual-currency system with Dollars ($) and Coins (◎).

### Starting Balance
- Dollars: $100
- Coins: 50 ◎

### Commands
- `/bal` - Check your balance
- `/bal <player>` - Check other's balance
- `/pay <player> <amount>` - Send dollars
- `/pay <player> <amount> coins` - Send coins
- `/baltop` - Richest players

### Exchange
**Note**: 2.5% fee • 100$ = 1◎

### Sell Items
**Tip**: Right-click a Composter to sell!

---

## land-claims
- **Name**: Land Claims
- **Icon**: `fa-shield-alt`
- **Color**: `text-emerald-400`
- **Background**: `bg-emerald-500/10`
- **Border**: `border-emerald-500/30`
- **Description**: Protect your builds with chunk-based regions.

### Limits
- Default: 2 regions, 10 chunks
- VIP: 4 regions, 20 chunks

### Commands
- `/rg create <name>` - Create region
- `/rg claim` - Claim chunk
- `/rg unclaim` - Unclaim chunk
- `/rg trust <player>` - Add member
- `/rg untrust <player>` - Remove member
- `/rg flags` - Manage permissions
- `/rg tp <region>` - Teleport to region
- `/rg deposit <amount>` - Fund region bank

### Upkeep
**Note**: $100/chunk/week • 1 week grace period

### Playtime Rewards
- 30 min: +1 chunk
- 1 hour: +2 chunks
- 3 hours: +4 chunks
- 1 day: +8 chunks

---

## death-chests
- **Name**: Death Chests
- **Icon**: `fa-skull`
- **Color**: `text-red-400`
- **Background**: `bg-red-500/10`
- **Border**: `border-red-500/30`
- **Description**: Your items are protected when you die!

### How It Works
- On Death: Items saved automatically
- Hologram: Shows at death location
- Particles: Guide you back
- Retrieve: Right-click hologram

### Timer
- Default: 5 minutes
- VIP: 30 minutes

### Commands
- `/rl list` - Active death chests
- `/rl deaths` - Expired chests
- `/rl retrieve` - Get queued items
- `/rl trust <player>` - Allow access

### Marketplace
**Tip**: Expired items can be bought by others - you get paid!

---

## combat
- **Name**: Combat
- **Icon**: `fa-khanda`
- **Color**: `text-orange-400`
- **Background**: `bg-orange-500/10`
- **Border**: `border-orange-500/30`
- **Description**: Classic 1.8 PvP mechanics - no attack cooldown!

### Features
- No Cooldown: Fast-paced combat
- Sword Blocking: Block to reduce damage
- Classic Knockback: Original mechanics
- Fishing Rod: Use for combos
- Golden Apples: Craftable enchanted

### Tips
**Tip**: Sprint hit for knockback • Block when low HP • Rods interrupt attacks

---

## shops
- **Name**: Player Shops
- **Icon**: `fa-store`
- **Color**: `text-blue-400`
- **Background**: `bg-blue-500/10`
- **Border**: `border-blue-500/30`
- **Description**: Create shops and sell items to other players.

### Create a Shop
- Step 1: Place a chest
- Step 2: Hold item to sell
- Step 3: Punch the chest
- Step 4: Set price in GUI

### Shop Tutorial
![Shop Creation Tutorial](https://via.placeholder.com/600x400/1a1a1a/ffffff?text=Shop+Creation+Tutorial)

### Commands
- `/shop create` - Create shop
- `/shop remove` - Remove shop
- `/shop collect` - Collect earnings
- `/shop list` - Your shops

---

## spawners
- **Name**: Spawners
- **Icon**: `fa-cube`
- **Color**: `text-purple-400`
- **Background**: `bg-purple-500/10`
- **Border**: `border-purple-500/30`
- **Description**: Stack spawners and collect drops via GUI!

### Features
- Stacking: Up to 64 spawners
- Virtual Drops: No mobs needed
- XP Collection: Get XP directly
- Hopper Support: Auto-collection

### Usage
**Tip**: Right-click spawner to open GUI and collect!

---

## villagers
- **Name**: Villagers
- **Icon**: `fa-user`
- **Color**: `text-amber-400`
- **Background**: `bg-amber-500/10`
- **Border**: `border-amber-500/30`
- **Description**: Pick up, claim, and manage villagers easily.

### Controls
- Pick Up: Shift + Right-click
- Place: Right-click ground
- Cooldown: 3 seconds

### Claiming
**Tip**: Claimed villagers are protected from others!

### Villager Hopper
**Note**: Hopper + Emerald Block = Auto-collect villagers

---

## essentials
- **Name**: Essentials
- **Icon**: `fa-home`
- **Color**: `text-cyan-400`
- **Background**: `bg-cyan-500/10`
- **Border**: `border-cyan-500/30`
- **Description**: Homes, warps, teleports, and more.

### Homes
- `/sethome [name]` - Set home
- `/home [name]` - Go to home
- `/delhome <name>` - Delete home
- `/homes` - List homes

### Teleport
- `/spawn` - Go to spawn
- `/tpa <player>` - Request teleport
- `/tpaccept` - Accept request
- `/back` - Previous location
- `/rtp` - Random teleport

### Other
- `/warp <name>` - Go to warp
- `/kit <name>` - Claim kit
- `/afk` - Toggle AFK
- `/msg <player>` - Private message

---

## crates
- **Name**: Crates
- **Icon**: `fa-gift`
- **Color**: `text-pink-400`
- **Background**: `bg-pink-500/10`
- **Border**: `border-pink-500/30`
- **Description**: Open crates for amazing rewards!

### Rarities
- Common: 70% (text-gray-300)
- Rare: 25% (text-green-400)
- Mythic: 5% (text-purple-400)

### Features
- Preview: Right-click crate
- Mass Open: Shift-click
- Milestones: Bonus rewards

### Get Keys
**Tip**: Vote, events, shop, achievements!

