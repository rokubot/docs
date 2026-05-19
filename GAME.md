# 🎮 Game

Welcome, adventurer, to the **Rokubot Merchant Empire**! Whether you seek to amass a fortune, slay beasts in the Iron Mines, or master the volatile arcane arts, your journey begins here.

This guide will teach you the mechanics of the economy, the risks of the wilderness, and how to outsmart your rival servers.

***

## 🔮 1. Choosing Your Destiny (`/start`)

To enter the world, type `/start`. You will be asked to choose a **Profession**. This choice is permanent and defines your role in the global economy!

* **🗺️ Wayfarer**: The ultimate gatherer. You are faster in expeditions and excel at finding raw materials.
* **🔨 Artificer**: The master crafter. You retain 10% more durability on items you forge.
* **✨ Mystic**: The arcane scholar. You gain a 5% XP bonus and are the **only** class that can brew potions and enchant gear.
* **📈 Tycoon**: The wolf of Wall Street. You pay a reduced market tax (only 3% instead of the standard 5%) when selling goods!

> **Tip:** You can always check your current stats, equipped profession, net worth, and full inventory using **`/profile`**.

***

## 🏕️ 2. Surviving the Wilderness

The economy runs on raw materials, and to get them, you must explore!

* **`/daily`**: A free daily stipend of coins and basic materials to keep you afloat.
* **`/explore`**: Embark on a solo expedition. As you level up (XP is gained from exploring, forging, brewing, and enchanting), you unlock deadlier, more lucrative zones like the _Whispering Woods_ or the endgame _Dragon's Peak_.

Watch out for **World Events**! If the _Dragon Migration_ or _Iron Famine_ is active, expedition durations and loot drops will dynamically change for the entire server!

***

## 💰 3. The Global Economy

The Merchant Empire features a fully player-driven economy.

* **`/market`**: Open the global marketplace. Here, you can buy materials and gear from other players, or list your own.
  * _Warning:_ The crown takes a **5% Tax** on all successful market sales (unless you are a Tycoon, who only pays 3%!).
* **`/trade`**: Want to avoid the market tax? Initiate a direct, secure, and atomic trade with another player. You can swap coins, raw materials, and specific enchanted gear all in one transaction!
* **`/pay`**: Instantly transfer coins to another player.

***

## ⚒️ 4. Crafting & The Arcane Arts

Why sell raw iron when you can forge a sword?

* **`/forge`**: Turn your raw materials into weapons and armor. Upgraded gear allows you to survive harder expeditions.
* **`/refine`**: Crush basic materials into advanced components (e.g., _Raw Mana_ → _Arcane Dust_).
* **`/brew`** _(Mystics Only)_: Use herbs and arcane dust to brew utility potions.
* **`/enchant`** _(Mystics Only)_: The ultimate gamble. Spend Arcane Dust to enchant your gear for massive stat boosts.
  * ⚠️ **DANGER:** Enchanting is highly volatile! If you fail the roll, your precious gear will **shatter into dust**! Do you have the courage to try?

> **Dynamic Spawns:** Keep an eye on active chat channels! If a channel is lively, **Volatile Mana Nodes** may spawn. Be the first to claim them to harvest Raw Mana! _(Note: Your Server Admins must configure these drops using the `/gamechannel` command!)_

***

## ⚔️ 5. Group Up: The Party System

The wilderness is dangerous alone. Form a party to take on high-tier expeditions!

* **`/party create`**: Found your own adventure group.
* **`/party invite @user`**: Invite up to 3 other friends.
* **`/party adventure`**: The party leader chooses a zone, and everyone embarks together!

**Class Synergies:** A diverse party is a powerful party. Having different professions in your group will stack passive buffs (e.g., having an Artificer and a Mystic gives the whole group durability retention _and_ an XP boost!).

***

## 🏆 6. Global Domination

Your wealth isn't just for you—it contributes to your entire Server's GDP!

* **`/gamelb`**: Check the cross-server leaderboards for Net Worth, Level, and Guilds.
* **`/rivalry`**: Every few weeks, the gods will pair the Top 20 servers into **1v1 Rivalry Duels**. Use this command to see who your server is fighting.
  * _The Goal:_ Generate more GDP than your rival server within 48 hours.
  * _The Prize:_ If your server wins, **every active player** receives a massive global loot drop!

### 🏅 Achievements

As you play, you will organically unlock achievements. Can you become a _Millionaire_? Can you forge a Tier 5 weapon to become a _Master Smith_? Check your `/profile` to see your badges of honor!

***

## ⚙️ 7. Server Configuration (For Guild Admins)

Are you a Server Admin? The RPG requires a tiny bit of setup to bring the world to life for your players!

These commands are available to anyone with the `Administrator` permission in your Discord server.

* **`/gamechannel`**: View the current status of surprise events (like Volatile Mana Nodes) and see the list of configured channels for your server.
* **`/gamechannel add [#channel]`**: Adds a specific text channel to the event drop list. Volatile Mana Nodes and other random drops will now occasionally spawn in this channel based on chat activity.
* **`/gamechannel remove [#channel]`**: Removes a channel from the event drop list.
* **`/gamechannel toggle`**: Globally enables or disables surprise events for your entire server.
