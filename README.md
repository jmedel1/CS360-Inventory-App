# CS360-Inventory-App
## Project Reflection (CS360 Mobile App Development)

### 1. Summary of Requirements and Goals
For this project, I built a mobile inventory app that lets a user create an account, log in, and manage a list of items. The goal was to give users a simple way to track items by name and quantity. The app was designed for people who need a basic inventory tool without anything complicated.

### 2. Screens and Features for User Needs
To support user needs, the app includes three main screens: a login screen, an inventory screen, and an SMS permissions screen.  
- The **login screen** lets users create an account and sign in.  
- The **inventory screen** lets users add, update, and delete items using a clean layout and a RecyclerView to show everything at once.  
- The **SMS screen** checks for permission and requests it so notifications can work.

I kept the UI simple by spacing things out clearly, labeling everything, and using straightforward buttons. I tested the screens often in the emulator to make sure they felt easy to use.

### 3. Coding Approach and Strategies
When I started coding, I broke the app into small pieces instead of trying to write everything at once. I made the database helper first, then connected it to the inventory screen, and then added the login system. I also added features one at a time so that if something broke, I knew where the problem came from. This step-by-step method is something I can use in future projects because it keeps things organized and easier to fix.

### 4. Testing and Why It Matters
I tested the app using the Android emulator after almost every change. This helped me catch layout issues, button mistakes, and incorrect database behavior right away. Testing showed me how important it is to check functionality early instead of waiting until the end. For example, I found out quickly when the RecyclerView wasn’t updating or when the SMS permission didn’t show the right message.

### 5. Challenges and Innovation
The biggest challenge was connecting the UI to the database and making sure the RecyclerView refreshed correctly. I had never used Android Studio before this course, so figuring out how adapters worked took some time. I solved issues by breaking down the code, testing small pieces, and looking back at examples until everything worked together.

### 6. Area of Strong Performance
I feel I was most successful in the inventory management feature. Getting add, edit, delete, and the RecyclerView display all working together showed my understanding of database operations, UI updates, and event handling. It was also the most complex part of the app, so getting it working smoothly felt like real progress.

