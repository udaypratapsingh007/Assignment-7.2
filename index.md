# Assignment 7.2 - Pricing Cards & Centered Login Form

## Pricing Cards

The three cards (Basic, Pro and Premium) sit inside the .pricing-cards container, which uses Flexbox.

- display: flex puts the cards in a row.
- justify-content: center centers the cards horizontally.
- align-items: stretch makes all cards the same height.
- flex-wrap: wrap moves the cards to the next line on small screens.
- gap adds equal space between the cards.

## flex-direction

- The .pricing-cards container uses flex-direction: row, so the cards sit side by side.
- Each .plan-card uses flex-direction: column, so its title, price, features and button stack vertically. margin-top: auto on the button pushes all buttons to the bottom of their cards.
- The login form also uses flex-direction: column to stack its fields.

## Centered Login Form

The .login-section is a flex container with justify-content: center for horizontal centering and align-items: center for vertical centering. With min-height: 100vh, the form is centered in the middle of the screen