# RecipeNest — Recipe App with Calories

A React + Vite recipe browsing project with recipe search, category filters, favorites, recipe details, meal basket serving controls, estimated calories per serving and total calories, plus a simple admin form to add recipes.

## Run locally
1. Install Node.js (LTS) if it is not installed.
2. Open this folder in VS Code.
3. Open Terminal in the project folder.
4. Run `npm install`
5. Run `npm run dev`
6. Open the local URL shown in the terminal (usually http://localhost:5173).

## Features
- Search recipes and filter by Breakfast, Lunch, Dinner.
- View ingredients and cooking steps.
- Save favorites (stored in browser LocalStorage).
- Add recipes to the meal basket and increase/decrease servings.
- Automatically calculate total estimated calories for selected servings.
- Admin panel to add recipes with calories per serving.
- Recipes and favorites are saved in LocalStorage.

## Notes
Calorie values are sample estimates per serving. They are not exact nutrition values and can vary by ingredient brands, recipe quantities, and portion size. LocalStorage is for a frontend demo; a real app should use a secure backend and admin authentication.


## Login details
- User: create an account using the Sign up tab.
- Admin: select Admin on the login page. Email: `admin@recipenest.com` Password: `admin123`.
- Admin Dashboard allows adding and deleting recipes.

This is a student demo: accounts and session data use browser LocalStorage. Do not use real or sensitive passwords. For production, implement secure server-side authentication.
"# frontend-project-foodrecipe" 
