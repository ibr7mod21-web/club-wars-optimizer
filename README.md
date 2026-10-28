# War Room: Club Wars Attack Optimizer

A free tool for SimCity BuildIt that works out the best use of your war items in Club Wars. Enter what is in your depot and it gives you the attack order that earns the most war points, along with the damage and energy for each attack.

**Use it here:** https://ibr7mod21-web.github.io/club-wars-optimizer/

It runs in your browser. There is no login, no ads, and nothing is sent anywhere.

## Quick start

1. **Pick your cards.** The first time you open it, tick the cards you have unlocked and enter the war points each shows in-game. You can change this any time under *Disaster card settings*.
2. **Enter your depot.** Type your war items or use the + and - buttons.
3. **Read the plan.** *Optimal Attack Plan* shows the best use of everything you have, sorted by points per energy. If you might get interrupted, fire from the top down.
4. **Press "Fire x1"** after each attack you cast in the game. The items come out of your depot and the plan updates.

## What else it does

- **Safest attack to fire right now:** the cast that costs your overall plan the least.
- **Safe to give teammates:** items left over after the best plan, so giving them away costs you nothing.
- **Bottleneck items:** items at zero that are blocking cards.
- **Best items to chase:** which items would add the most points if you got more.
- **Energy-bank burst planner:** the best attacks to fit inside one energy bank, including lining up hits for a Jackpot booster.
- **Damage tracking:** damage per attack and in total.

## Points depend on your card levels

Recipes, energy and damage are the same for every player. War points are not: they rise with card level. At Level 1 an attack is worth about 100 points per point of damage, and each level adds roughly 10%. The tool starts with Level 1 values, so enter the points your own cards show. The plan is only as accurate as those numbers.

## Your data

Your depot and settings are saved in your own browser, on the device you use. A phone and a laptop will not share them, and clearing your browser data will erase them. The "Reset everything" link at the bottom clears them on purpose.

## Accuracy

The attack list (recipes, energy, damage) comes from the SimCity wiki and was checked against a live account for 14 of the 24 cards. The rest come from a single source and may be out of date, so check any card you rely on against the game. Three cards have special behavior (Zest from Above, Electric Deity, Doomsday Quack) and carry notes in the card list. You can edit any recipe, damage or energy value, or add a new disaster, under *Disaster card settings*.

## The plan is exact

The planner searches for the true best combination of attacks for your depot. It is not a rule of thumb, so no other combination of the same items scores higher.

## Files

Everything lives in one file, `index.html`, published with GitHub Pages.

## Credit

Made by **Brrville** (friend code PJ3S8B).

Unofficial fan tool for SimCity BuildIt. Not affiliated with or endorsed by EA or Maxis.
