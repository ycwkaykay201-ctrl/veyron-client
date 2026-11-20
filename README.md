# Veyron Client

**A modern, fast launcher for Minecraft: Java Edition on Windows.**

Veyron Client is a desktop launcher built with C# and .NET 10 (WPF). It is being developed in phases toward a full PvP-focused client with performance and HUD mods.

## Features

- Clean, dark interface with live accent colours
- Every release and snapshot from Mojang's official version list
- Fast, verified downloads of game files straight from Mojang
- Automatic setup of Mojang's official Java runtime for each version
- Memory, resolution and JVM settings
- Recently played history

## Sign-in and game ownership

Veyron signs players in with their **Microsoft account** using Microsoft's device code flow. Players enter a short code on Microsoft's own website, so Veyron never sees their password.

After sign-in, Veyron goes through Xbox Live and Minecraft services and checks the player's Minecraft profile to **confirm they own Minecraft: Java Edition before the game can be launched**. There is no offline or cracked mode. Only an encrypted sign-in token is stored, on the player's own PC (Windows DPAPI).

## Roadmap

- One-click Fabric installs and mod management
- Built-in client modules (FPS display, keystrokes, zoom and more)
- Skin preview

## Status

In active development. Not affiliated with or endorsed by Mojang or Microsoft.
