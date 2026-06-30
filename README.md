# RUN.EXE — Escape the Game

> *You were speedrunning. Then the game loaded you in.*

## What is this?

RUN.EXE is a pixel-style platformer where you play as RUNNER — a speedrunner trapped inside a game by a mysterious developer known only as DEV. Your only guide is ECHO, a glitching AI companion who helps you escape through 10 corrupted levels. But can you trust her?

Every level introduces a new glitch mechanic that you must exploit to survive and progress. The glitches aren't bugs — they're your weapons.

---

## How to Play

| Control | Action |
|--------|--------|
| Arrow Keys / WASD | Move |
| Up / W / Space | Jump |
| Z or J | **Swing sword** (also deflects enemy shots!) |
| X or Shift | **Glitch power** (unique per level) |
| Q / E | **Switch sword** (cycle unlocked weapons) |

### Deflect System
When you swing your sword (Z), a deflect zone appears in front of you. Any enemy projectile that enters that zone gets sent back toward the enemy or boss. Deflecting rewards you with +15 Glitch Energy. Time your swings to turn enemy fire against them.

---

## Glitch Mechanics

Each level unlocks a new sword and glitch power. The glitch powers are the core mechanic required to progress.

| Level | Sword | Glitch Power (X) | Required to Progress |
|-------|-------|-----------------|---------------------|
| 1 | Glitch Dagger | CLIP — phase through marked walls | ✅ Yes — walls block every path |
| 2 | Frost Blade | FREEZE — stop all enemies cold | Recommended |
| 3 | Corrupt Sword | CORRUPT — area destroy nearby enemies | Boss level |
| 4 | Phase Blade | PHASE — 2 seconds of invincibility | Useful for armored sections |
| 5 | Warp Sabre | WARP — teleport 200px forward | ✅ Yes — gaps too wide to jump |
| 6 | Twin Blades | CLONE — spawn a decoy enemy magnet | Recommended |
| 7 | Crash Axe | CRASH — area kill burst | Boss level |
| 8 | Echo Sword | REWIND — roll back 2 seconds | Recommended |
| 9 | Overload Blade | OVERLOAD — screen-wide nuke | Recommended |
| 10 | Null Blade | NULL — delete everything nearby | Boss level — final fight |

### How Glitches Are Triggered
- Stand near a **marked wall** (teal outline, shows `??`) and press **X** to clip through it
- Press **X** at any time to activate the current level's glitch power
- Glitch Energy (pink bar) is consumed on use — collect coins and kill enemies to refill it
- **Deflect** is always available during any sword swing regardless of energy

---

## Level Structure

- **10 levels** total
- **Levels 1, 2, 4, 5, 6, 8, 9** — standard platforming with escalating enemies
- **Level 3** — Mini Boss: GUARDIAN_v1
- **Level 7** — Mini Boss: CRASH_DAEMON  
- **Level 10** — Final Boss: DEV (3 phases)

Boss levels have **no regular enemies** — just you, the boss, and heart items scattered around the arena.

---

## Items

- **Yellow circles** — Coins (+50 score, +glitch energy)
- **Pink hearts** — Healing items (+1 or +2 HP)
- **? blocks** — Break with sword for bonus coins

After clearing each level you receive a **weapon item** (dagger, shield, sword, boots, etc.) that expands your arsenal permanently.

---

## Story

RUNNER was speedrunning a game when the game loaded him inside it. DEV, the game's creator, has built a prison out of corrupted code. ECHO — a glitching AI companion — appears to guide RUNNER out. She floats beside you, cheers you on, warns you of danger, and reacts to everything. But ECHO was built by DEV. Her real purpose is to deliver RUNNER to the CORE so DEV can absorb his glitch power.

By Level 6, RUNNER discovers the truth. ECHO confesses — and chooses him over DEV. Together they fight to the final level to destroy DEV and free themselves from the game.

The final choice: defeat DEV, or become part of the system forever.

---

## Known Limitations

- Clip walls on Level 1 require being close to the wall before pressing X — if X doesn't work, move right up against the wall
- The deflect window lasts ~14 frames — swing just before a shot reaches you, not after
- On mobile/touchscreen, use the on-screen FIRE and POWER buttons; Q◀ and ▶E buttons switch weapons
- Level 10 has no exit door — the level ends automatically when DEV is defeated

---

## Built With

- Vanilla HTML5 Canvas + JavaScript (no external game engine)
- Zero dependencies — single `.html` file, runs entirely in browser
- Pixel art drawn programmatically using Canvas 2D API with fake-3D shading
- All character sprites, animations, and effects built from scratch

---

## Controls Summary (Quick Reference)

```
Z     → Swing sword / Deflect shots
X     → Glitch power (level-specific)
Q/E   → Switch between unlocked swords
Arrows/WASD → Move
Up/Space    → Jump
```

*Defeat DEV. Free ECHO. Escape the game.*
