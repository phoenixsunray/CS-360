# CS-360
Mobile Architect &amp; Programming

# CS 360 Inventory App Reflection

## App Requirements and Goals

The app I developed is an inventory tracking app designed to help users manage warehouse inventory from a mobile device. The main requirements were to allow users to create an account, log in, add inventory items, view inventory in a grid, update item quantities, delete inventory items, and receive SMS notifications when an item reaches zero. This app was designed to meet user needs such as quickly checking stock, updating inventory during a shift, and being alerted when an item needs to be restocked.

## User-Centered UI Design

The app required three main screens to support the user’s needs. The login screen allows users to enter a username and password or create a new account. The inventory screen allows users to add items, view current inventory, increase or decrease item quantities, and delete items. The SMS notification screen allows users to enter a phone number and choose whether to allow low-inventory text alerts. My UI design kept users in mind by making each screen focused on one main task. I used clear labels, simple buttons, and an organized layout so users could understand what each screen was for without confusion. I believe the design was successful because the app is easy to navigate and the most important actions are easy to find.

## Coding Approach

I approached the coding process one step at a time. I started with the login and account creation features, then added the SQLite database for storing users and inventory items. After that, I connected the inventory screen to the database so users could add, view, update, and delete records. Finally, I added SMS permission handling and low-inventory notifications. This strategy helped make the project easier to manage because I could build and test one feature before moving to the next. I can apply this same technique in future projects by breaking large tasks into smaller sections and testing each part as I go.

## Testing

I tested the app using the Android Emulator in Android Studio. I tested creating a new account, logging in, adding inventory items, increasing and decreasing item quantities, deleting items, and using the SMS notification feature. I also tested what happened when SMS permission was allowed and when it was denied. Testing was important because it showed whether the app worked as expected and helped identify problems before submission. It revealed issues such as needing to update the database version and making sure each button was connected to the correct function.

## Innovation and Challenges

One challenge I had to overcome was turning the UI design from Project Two into a fully functional app in Project Three. The screens already existed visually, but they still needed to be connected to working Java code and a SQLite database. I had to adjust the app so the inventory grid displayed real database information instead of sample rows. I also had to make sure the SMS feature was optional so the app would still work if a user denied permission. I solved these challenges by testing often and fixing one issue at a time.

## Area of Success

I was particularly successful with the inventory database portion of the app. The app allows users to create, read, update, and delete inventory records, which demonstrates my understanding of SQLite database operations in Android Studio. I was also successful in making the app handle SMS permissions correctly. The app can send a low-inventory alert when permission is granted, but it still continues to work when permission is denied. This showed that I could create a functional app while keeping the user experience in mind.
