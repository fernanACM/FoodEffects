# FoodEffects
[![](https://poggit.pmmp.io/shield.state/FoodEffects-PM4)](https://poggit.pmmp.io/p/FoodEffects-PM4)

[![](https://poggit.pmmp.io/shield.api/FoodEffects-PM4)](https://poggit.pmmp.io/p/FoodEffects-PM4)

**The best food supplement with positive/negative effects. Enhance your abilities with FoodEffects, or damage your enemy with food with negative effects.**

![icon-foodeffects](https://user-images.githubusercontent.com/83558341/178093862-6ac32c03-49da-4b29-b18c-421d8ca1e4be.png)

### 📢 Information
With this plugin, you are able to assign different effects to items so that when a player interacts with or consumes that item, they are given the effect for a set duration at a set effect level! The format along with some examples for the item listing can be found in both the *config.yml* file and down below if you ever get confused. If you would like a video example of the plugin in action, click [here](https://youtu.be/SbITnMk8jVE)

### 🍎 Item Formatting
```yaml
"Item-ID:Item-Damage:
    "Name": "Custom-Name"
    "Effects":
        - [Effect-ID,Effect-Amplifier,Effect-Duration]
        - [Effect-ID,Effect-Amplifier,Effect-Duration]
        - [Effect-ID,Effect-Amplifier,Effect-Duration]
```

### 🍗 Item Listing Example
Desired configuration:
* When steak(ID = 364) is consumed, give blindness(ID = 15) level 1 for 10 seconds and strength(ID = 5) level 2 for 30 seconds
* When an apple(ID = 260) is consumed, give speed(ID = 1) level 3 for 15 seconds and night vision(ID = 16) level 1 infinitely(0)
* When interacting with a jungle sapling(ID = 6:3), give slowness(ID = 2) level 1 for 60 seconds, fire resistance(ID = 12) level 1 for 30 seconds, and speed(ID = 1) level 3 for 5 seconds
* When interacting with a red mushroom(ID = 40), give slowness(ID = 2) level 1 for 5 seconds

Configuration in config.yml:
```yaml
Consumables:
  "364:0":
    "Name": "§aAwesome §6Steak"
    "Effects":
      - [15,1,10]
      - [5,2,30]
  "260:0":
    "Effects":
      - [1,3,15]
      - [16,1,0]

Non-Consumables:
  "6:3":
    "Effects":
      - [2,1,60]
      - [12,1,30]
      - [1,3,5]
  "40:0":
    "Name": "§bLuck §cMushroom"
    "Effects":
      - [2,1,5]
```
### 📞 Contact 
| Redes | Tag | Link |
|-------|-------------|------|
| YouTube | fernanACM | [YouTube](https://www.youtube.com/channel/UC-M5iTrCItYQBg5GMuX5ySw) | 
| Discord | fernanACM#5078 | [Discord](https://discord.gg/YyE9XFckqb) |
| GitHub | fernanACM | [GitHub](https://github.com/fernanACM)
| Poggit | fernanACM | [Poggit](https://poggit.pmmp.io/ci/fernanACM)
****

### ✔ Credits
* [Xenophilicy](https://github.com/Xenophilicy/)
