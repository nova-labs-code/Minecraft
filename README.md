# Minecraft Survival Checklist

A browser-based Minecraft Survival Checklist for tracking survival goals and Xbox achievements.

## Features

- Survival checklist with multiple categories
- Shared survival-goal progress
- Up to 12 player profiles
- Individual achievement progress for each player
- Xbox Achievement Gamerscore tracking
- Global score tracking
- Current Global Score / Total Possible display
- Difficulty-based scoring for survival goals
- Search through goals and achievements
- Collapsible categories
- Only one category can be open at a time
- Custom profile creation, editing, and deletion
- Local progress saving with `localStorage`
- Responsive design for mobile and PC
- No account or server required

## Scoring

Normal survival goals use difficulty-based scoring:

| Difficulty | Points |
|---|---:|
| Easy | 10 |
| Medium | 25 |
| Hard | 50 |
| Epic | 100 |

Xbox achievements use their actual Gamerscore value.

### Global Score

Normal survival goals are shared between everyone.

Achievements are tracked separately for each profile.

The Global Score is calculated as:

```text
Shared Goal Score
+
Achievement Score from Profile 1
+
Achievement Score from Profile 2
+
...