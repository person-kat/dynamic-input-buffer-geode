# Predictive Input Buffer (Geode Recreation)

Recreation of the **Predictive Input Buffer** mod based on the v4.7 console log.
This is not the original code: it is a reimplementation of the observed behavior.

## Behavior

- Inputs (press / release) are queued and applied **N ticks later** (1 tick = 1/240 s).
- **F6** cycles through the stages within a level:

| Stage | Ticks (all) | Ticks (wave) |
|-------|-------------|--------------|
| 1     | 2           | 2            |
| 2     | 4           | 4            |
| 3     | 8           | 8            |
| 4     | 16          | 8            |
| OFF   | raw input   | raw input    |

ALL CREDITS FOR MAKING THE MOD TO jolanwxf
