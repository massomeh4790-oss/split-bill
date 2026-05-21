# 💰 Split Bill App

A simple and interactive React application to manage friends, track balances, and split bills evenly.

## 🚀 Features

- ✅ View a list of friends with their current balance
- ✅ Add new friends with name and profile image
- ✅ Select a friend to split a bill with
- ✅ Split bill between you and the selected friend
- ✅ Automatically update balance based on who pays
- ✅ Responsive and clean UI

## 🛠️ Technologies Used

- React (Functional Components & Hooks)
- JavaScript (ES6+)
- CSS (for styling)

## 📸 Screenshots

_(Add screenshots of your app here)_

## 📦 Installation

To run this project locally:

```bash
# Clone the repository
git clone https://github.com/your-username/split-bill-app.git

# Navigate to the project folder
cd split-bill-app

# Install dependencies
npm install

# Start the development server
npm start
🧠 How It Works
Friends List – Displays all friends with their current balance status.

Add Friend – Fill in name and image URL to add a new friend.

Select Friend – Click "Select" to open the split bill form.

Split Bill – Enter bill total, your expense, and choose who pays.

Balance Update – The balance updates instantly based on your selection.

📁 Project Structure
text
src/
├── index.js        
├── Split.js    
└── Split.css        
🧩 Component Overview
Component	Purpose
App	Holds all state and main logic
FriendsList	Renders the list of friends
Friend	Displays individual friend info and select button
Button	Reusable button component
FormAddFriend	Handles adding a new friend
FormSplitBill	Handles splitting a bill with selected friend
🧪 Example Logic
If you pay the full bill, the friend owes you money → their balance increases.

If the friend pays the full bill, you owe them → their balance decreases.

Even split sets balance to zero.

🔮 Future Improvements
Add local storage to persist data

Edit or delete friends

Currency selection

Split bill among multiple friends

Add authentication to save user-specific data

📄 License
This project is open-source and available under the MIT License.

🙌 Acknowledgments
Built as part of a React learning exercise

Inspired by Jonas Schmedtmann's React course

Author: Massomeh ;)

Happy splitting! 🍻

