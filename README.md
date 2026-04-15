# MacroSolver

A mobile-first macro calculator that solves the **reverse lookup problem**: given your target macros (protein, carbs, fat), it tells you exactly how many grams of each food to eat.

Most macro apps go food → macros. MacroSolver goes macros → food.

## Features

- **Typeahead search** across 40+ foods with live filtering
- **Optional fat source** — enables 3-food solver for better fat macro accuracy
- **Per-food raw/cooked toggle** — shows cooked grams or raw grams with conversion note
- **USDA source links** on every food — tap to verify the exact FoodData Central entry
- **Least-squares solver** — finds the closest possible solution when two foods can't perfectly hit all three macros
- **Gap warnings** — flags any macro more than 10g off target
- No login, no backend, no tracking — runs entirely in your browser

## Food Categories

**Proteins:** Chicken (4 cuts), Ground Beef (5 grinds: 70/30–93/7), Fish (salmon, tuna, tilapia, shrimp), Pork (3 cuts), Other (eggs, turkey, cottage cheese, Greek yogurt)

**Carbs:** Rice & grains, Potatoes (russet, Yukon Gold, sweet), Legumes, Bread, Fruit

**Fats (optional):** Butter, Ghee, Olive Oil, Coconut Oil, Avocado, Peanut Butter, Almond Butter, Almonds, Walnuts, Cashews

## Usage

Just open `index.html` in any browser. No build step, no dependencies, no npm.

For mobile use: deploy to Netlify (free), then add to your phone's home screen via browser → Share → Add to Home Screen.

## Deployment (Netlify)

1. Fork or clone this repo
2. Go to [netlify.com](https://netlify.com) → New site → Import from GitHub
3. Select this repo — no build settings needed
4. Deploy — you get a live URL in ~30 seconds

## Data Sources

All macro data sourced from [USDA FoodData Central](https://fdc.nal.usda.gov/).
Cooking yield factors from [USDA Table of Cooking Yields for Meat and Poultry, Release 2](https://www.ars.usda.gov/northeast-area/beltsville-md-bhnrc/beltsville-human-nutrition-research-center/methods-and-application-of-food-composition-laboratory/mafcl-site-pages/cooking-yields/).

## Roadmap

- [ ] Meal saving / history
- [ ] Custom food entry
- [ ] Multi-meal daily planner
- [ ] PWA / installable app

## License

MIT
