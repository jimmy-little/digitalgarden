---
{"dg-publish":true,"permalink":"/the-blog/apple-s-trojan-horse-services-edition/","tags":["apple"]}
---

![appletrojanhorse.png](/img/user/The%20Blog/img/appletrojanhorse.png)

Remember [Game Center][gc]? Introduced in 2010 with iOS 4, it was Apple’s nod to the Xbox Live crowd: casual leaderboards, achievements, and turn-based game tracking. It was delightful for a while. Then in 2016, Apple unceremoniously pulled the plug—not on the service itself, but on the idea of it as a destination.

Game Center became just another modal overlay. No more central hub. No more glanceable status across games. For me, that marked the end of using my phone for gaming. (Well, that and the escalating horror show of 2016-era politics.)

Now, almost a decade later, Apple’s bringing it back. Not as Game Center, but as a new standalone app called **Apple Games**. Turn-based tracking, leaderboards, challenges—it’s all here again. And there’s something new: a dedicated in-app App Store for games.

That last bit might seem minor, but it’s not. It’s a signal. And when [Marco Arment mentioned on ATP][atp] that Apple Games resembles the Apple TV app, I couldn’t stop thinking about what that might really mean.

Let’s lay out what we know.
- Apple's biggest growth sector is **services**.
- The biggest driver of services is the **App Store**.
- The biggest moneymaker in the App Store is **Games**.

Games account for most of App Store revenue. We’re talking tens of billions annually. Not from AAA ports or Apple Arcade indies, but from casino-style, gem-buying, idle-tapping, whale-chasing freemium games.

These games aren’t pushing the limits of Metal or the Neural Engine. Most are just lightweight Unity or JavaScript builds running inside wrappers. In other words: they don’t need iOS. They just need a platform.
### The Trojan Horse
Consider this: Apple Music and Apple TV aren’t iOS-exclusive. They’re on Android. They’re on smart TVs. Why? Because they drive recurring revenue.

**_Apple Games_ could be next.**
### But How?
Imagine an Apple Games app on Android. Not a launcher. Not a companion. A full-fledged runtime—maybe even with a lightweight emulator—capable of running a vast majority of “Apple Games” without requiring Google Play.

Millions of these games would just work. And they’d carry with them all the App Store trimmings: Game Center leaderboards, turn-based matchmaking, in-app purchases powered by Apple ID.

It’s not a technical stretch. It’s a strategic land grab.

### OK, But Why?
1. **Market Expansion** – Apple’s stuck at ~20% global smartphone share. Android holds the rest. Bringing Apple Games to Android multiplies their TAM[^TAM] with no new hardware.
    
2. **Developer Appeal** – Unity devs making clones and casino games don’t want to manage separate pipelines. Apple could pitch them a new “write once, run anywhere” promise—with Game Center APIs as the glue.
    
3. **Regulatory Relief** – Apple is under antitrust fire. Offering cross-platform access could blunt criticism that they lock users and devs into a walled garden.
    
4. **New Revenue** – Apple’s cut of in-app purchases could follow the user, even on non-Apple devices. That’s enormous, and very typical of Tim Cook's Apple.

## Developers Developers Developers
For cross-platform devs:

> “You no longer need to build for iOS _and_ Android. Build for Apple Games. We’ll run it everywhere. Leaderboards, billing, achievements—it’s all taken care of.”

For iOS-only indies:

> “You don’t need to touch Android. If your game runs in Apple Games, it _runs_ on Android—zero code changes.”

That’s an incredibly attractive value prop. And unlike Apple Arcade which chases prestige, Apple Games for Android would chase **scale**.

### Last Word
Apple doesn’t need to own the hardware to own the experience. They already have the games. They already have the billing relationships. They already have the APIs. They just need to ship the runtime—and call it Apple Games.

It’s not about winning the console war. It’s about redefining the App Store war.

[gc]: https://en.wikipedia.org/wiki/Game_Center
[atp]: https://atp.fm/643
[^TAM]: Total Addressable Market

