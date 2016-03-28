# OnTap

Minimal work to be done (for a grade of C):

Provide basic Thirstbuster client app functionality. Some things a basic system has to support include:

Nice app icon, launches and opens smoothly.

Provides a way to enter a client's name and payment information at first run.

Provides a way to browse the drinks menu for an establishment.

Provides a way to start a drink order, and place drinks on the order, then submit.

Shows status of evolving orders, drawn from data posted in the shared data channel by the web-app side.

Provides some way of handling the "verification of drink receipt" problem discussed in the spec.

At least a way to handle the "self-serve" mode, meaning the client comes to the counter to get the order.
--This avoids implementation of the second, small "server-app" mentioned in the spec.

Reasonable quality UI --- clean, aesthetic, smooth function. Serious points here.


Screens to be completed:
- Login Screen (start screen)
- Account creation (Email/pass)
- Account creation (Payment/billing info)
- Home Screen (Order drinks / manage account)
  - ALERT (ENTERING OnTAP ID)
- MyTab (drink tab / place order / order status)
  - ALERT (ADDING DRINK)
  - ALERT (PLACE ORDER)
  - ALERT (ORDER READY)
- Drink categories (Alcoholic)
- Drink categories (Non-alcoholic)
- Categorized drink menu (specific to category)
  - ALERT (ADDING DRINK)
- Account management screen (update / delete account)
- Update account information
- Update billing information
- Delete account
  - ALERT (DELETE ACCOUNT CONFIRMATION)
