### Evening 👋

I like code that's correct, fast and readable. I'd say "in that order" but that would imply one can't have all three.

As you might have noticed, I am a fan of Rust. I also write games in it:

- [RecWars](https://github.com/martin-t/rec-wars) is a free and open source clone of RecWar, a 2D multiplayer tank shooter - 3 vehicle types, 8 weapons, 3 game modes and lots of maps. Still very WIP, but playable. Has a [browser version](https://martin-t.gitlab.io/gitlab-pages/rec-wars/macroquad.html).

  RecWars originally started as a small project to evaluate Rust for gamedev before moving onto a 3D game. Well, turns out everything in Rust is still a bit immature so it's taking way longer than planned. Also kinda because I rewrote the whole thing several times as a "learning experience". But I am getting there, just one more redesign and maybe one more engine switch and everything's gonna be perfect.

- [RustCycles](https://github.com/rustcycles/rustcycles) is a fast-paced first-person  multiplayer shooter. Except you're not a boring old guy walking around, you're driving a motorbike, you can't stop and you can't go in circles because you're leaving a force-field wall behind yourself. So you better come up with a plan fast before you crash. And you better think clearly under fire because other people are gonna be shooting at you. Know [Tron](https://www.youtube.com/watch?v=c1Eeu0lsozc&t=51s)? That, with guns.

  Currently RustCycles is a very early proof of concept developed in parallel with RecWars - both games share a lot of the architecture even though they use different engines.

Finally, if you're also interested in gamedev, you might like my library, [cvars](https://crates.io/crates/cvars). It's a Rusty take on how games have been storing and managing configs since Quake 1. Includes consoles for Macroquad and Fyrox.

![Macroquad console](https://github.com/martin-t/cvars/raw/HEAD/cvars-console-fyrox/screenshot.png)

![Fyrox console](https://github.com/martin-t/cvars/raw/HEAD/cvars-console-macroquad/screenshot.png)
