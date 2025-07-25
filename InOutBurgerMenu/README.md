# InOutBurgerMenu 🍔🍟🥤

A simple, database-free Ruby on Rails 7 web app that mimics the style of an In-N-Out Burger menu. Orders are stored in user session only.

## Features

- Menu for burgers, fries, and drinks
- Quantity selector for each item
- Order summary after submission
- Classic burger joint styling
- No database required

## Run Locally

1. Install Rails and dependencies:
   ```bash
   bundle install
   ```

2. Start the server:
   ```bash
   rails server
   ```

3. Visit `http://localhost:3000`

## Deploy on Railway

1. Push this app to a GitHub repository.
2. Sign in at https://railway.app/
3. Create a new project and link your GitHub repo.
4. Set the startup command as:
   ```bash
   bundle exec rails server -b 0.0.0.0 -p $PORT
   ```
5. Deploy and enjoy!

*No database needed. Just delicious burgers and code.*