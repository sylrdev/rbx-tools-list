## Data
- ProfileStore: https://madstudioroblox.github.io/ProfileStore/ -> Industry standard, ability to make non player oriented data stores + fragment player data in multiple stores
- Lapis: https://nezuo.github.io/lapis/ -> Built-in migration, compatibility with T, promise based API
- Lyra: https://paradoxum-games.github.io/lyra/ -> Similar to Lapis, built-in transactions for trading

## UI
- Vide: https://centau.github.io/vide/ -> New industry standard, recommended over ReactLuau or Fusion in new projects, easy and fast to use
- Ripple: https://github.com/littensy/ripple -> Provides extra animations than can be used with ReactLuau or Vide if springs are not enough
- Fluid: https://ffrostfall.github.io/fluid/ -> Forked from Vide, apparently faster, better named API, async support and better supported by strict Luau
- Liquid: https://github.com/teamfireworks/liquid -> Provides useful hooks to use with Fluid
- UI Labs: https://ui-labs.luau.page/ -> Studio plugin + lib to preview UI components without emulating

## Dev Tools
- Conch: https://alicesaidhi.github.io/conch/ -> Industry standard command console, deep role + permission based configuration (like Discord)
- Lori: https://github.com/KYRORBLX/Lori -> Quick silent debugging tool, think of it like a simpler micro profiler
- Konsole: https://github.com/KYRORBLX/Konsole -> Command console, same author as Lori, good alternative to Conch if you don't mind less customizable permissions are not an issue
- Iris: https://sirmallard.github.io/Iris/ -> Immediate GUI library, meant to be used a debugging tool to test systems before building proper UI

## Networking
- TypedRemote: https://sleitnick.github.io/RbxUtil/api/TypedRemote/ -> Declarative typed remote events and functions
- Zap: https://zap.redblox.dev/ -> CLI based declarative remote management, uses its own config file, fast (I personally don't like having a cli tool JUST to generate remotes)
- Blink: https://1axen.github.io/blink/ -> CLI based declarative remote management, uses its own config file, faster? (same thing, don't like it), has a VSCode extension

## Signal
- Signal: https://sleitnick.github.io/RbxUtil/api/Signal/ -> Reliable
- NamedSignal: https://personal.averlyst.dev/NamedSignal/ -> Strict Luau support
- LemonSignal: https://data-oriented-house.github.io/LemonSignal/ -> Fastest

## Runtime type checking
- T: https://github.com/osyrisrblx/t -> Reliable, good symbiosis with some other libs (Lapis & Lyra)
- GreenTea: https://corecii.github.io/GreenTea/ -> Modern alternative to T + has T migration built-in, strict Luau compatible
- Boba: https://github.com/welcomestohell/boba -> Said to be the best overall but also unmaintained since the author moved to GreenTea, type checkers can be converted to actual types

## Garbage collector
- Trove: https://sleitnick.github.io/RbxUtil/api/Trove/ -> Same author as Signal, reliable
- Janitor: https://howmanysmall.github.io/Janitor/ -> Faster than Trove
- Scythe: https://github.com/synttx/oss/tree/main/packages/scythe -> Modern, newer alternative, extremely memory performant

## ECS
- Jecs: https://010devx101.github.io/jecs-docs/ -> Industry standard, developed by the co-author of Matter
- Jabby: https://alicesaidhi.github.io/jabby/ -> Debugging for Jecs
- Matter: https://matter-ecs.github.io/matter/ -> Older but provides more functionalities than Jecs, only use if you need those, otherwise stick to the lighter, more efficient Jecs

## Async handler
- Promise: https://eryn.io/roblox-lua-promise/ -> JavaScript promise ported to Luau
- Future: https://util.redblox.dev/future.html -> Industry standard? newer than Promise
- Vow: https://github.com/synttx/oss/tree/main/packages/vow -> Newest, same other as Scythe

## State
- Charm: https://github.com/littensy/charm -> Industry standard, good integration with Vide UI, atomic
- Reflex: https://littensy.github.io/reflex/ -> Same author as Charm, use this if you're used to the Redux workflow

## Other libs
- Chrono: https://parihsz.github.io/Chrono/ -> Custom computed physics replication (good if Roblox native physics are too slow for you)
- ObjectCache: https://devforum.roblox.com/t/objectcache-a-modern-blazing-fast-model-and-part-cache/3104112 -> object polling

## CLI
- Rokit: https://github.com/rojo-rbx/rokit -> roblox cli tool manager
- Rojo: https://rojo.space/ -> Industry standard code editor to Roblox Studio sync, very well established, the name is the Spanish for red
- Azul: https://azul.ransomwave.games/ -> Alternative to Rojo, two way sync, the name is the Spanish for blue
- Argon: https://argon.wiki/ -> Modern alternative to Rojo, Id still use rojo over argon unless you have a specific reason to use Argon
- Wally: https://wally.run/install -> First Roblox package manager, developed by the Team behind Adopt Me
- Wally package types: https://github.com/JohnnyMorganz/wally-package-types -> Imports public types to Wally imported packages cause Wally doesn't do it
- Pesde: https://docs.pesde.dev/ -> Becoming the new industry standard package manager, support the Wally index so any Wally package can be installed through Pesde
- LPM: https://luaupm.com/ -> Newest package + tool manager, will most likely overshadow Wally, Pesde and Rokit as its all in one and supports both the Wally and Pesde index
- Lest: https://lest-luau.github.io/lest/ -> Runtime testing suite
- Tungsten: https://pwnwrkz.github.io/tungsten/ -> Asset manager, batch upload assets to Roblox instead of doing it manually through the online laggy interface

# Realms Legacy Stack
- ProfileStore
- Vide
- Conch
- TypedRemote
- Boba
- Trove
- Charm + CharmSync
- Rokit
- Rojo
- Wally + Wally Package Types
- Tungsten
