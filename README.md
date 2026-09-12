# ചോരും തോറും കോരാം! 💧🥄
### The Most Useless Water-Filling Challenge Ever! 🤡

> "എന്തിനാണ് ചെയ്യുന്നത് എന്ന് അറിയില്ല... പക്ഷേ ചെയ്യാതിരിക്കാനും പറ്റില്ല!" 😌

---

## 🎯 Basic Details

### Omlette 

### Team Members

- **Team Lead:** Mayookha R- College of Engineering Karunagappally 
- **Member 2:** Anaswara Harish- College of Engineering Karunagappally 

---

## 💡 Project Description

**ചോരും തോറും കോരാം!** is a completely unnecessary but highly entertaining digital experiment.

The challenge is simple: use a spoon to fill a leaking bottle with water within **60 seconds**. The problem? The bottle has holes, and the holes become increasingly dangerous as you continue pouring.

The project measures how much time, water, and effort you are willing to waste on something that absolutely does not need to be done. 😂

---

##  The Problem (That Doesn't Exist)

### "How can we efficiently fill a bottle that is intentionally designed to leak?"

Nobody asked this question.

Nobody needed a solution.

But we decided to solve it anyway. 

The user has to repeatedly pour water into a leaking bottle while:

- The water keeps escaping 
- More holes appear 
- Existing holes become wider
- Time keeps running ⏱️
- The user slowly questions their life choices 

---

## 🧠 The Solution (That Nobody Asked For)

We created an interactive browser-based game where the player attempts to fill a **500 ml virtual bottle** using a **25 ml spoon**.

### The rules are beautifully pointless:

1. Start the challenge 
2. Click **"🥄 കോരി ഒഴിക്കുക"** to pour one spoon of water.
3. Each spoon adds **25 ml** of water.
4. The bottle starts with **5 holes**.
5. Every **3 spoons**, the leakage gets worse.
6. After the first 3 spoons, the number of holes doubles to **10**.
7. After that, the holes become progressively wider and leak faster.
8. You have only **60 seconds**.
9. Try to reach **500 ml**.
10. Stop whenever you realise what you're doing with your life. 😂

---

# ⚙️ Technical Details

## Technologies / Components Used

### For Software

- **HTML5** – Structure of the web application
- **CSS3** – Styling, responsive layout and animations
- **JavaScript** – Game logic, timer, water calculation and interactions
- **SVG** – Bottle, spoon and water graphics
- **CSS Animations** – Spoon pouring and water-flow animations
- **VS Code** – Development environment
- **Web Browser** – Running and testing the project

### For Hardware

No special hardware is required.

The project runs completely in a web browser.

---

# 🛠️ Implementation

## Game Architecture

The project is divided into three main screens:

### 1. Introduction Screen 🚀

The first screen introduces the challenge and explains the rules.

It contains:

- Project title
- Funny introduction
- Challenge description
- Start button

Clicking **"തുടങ്ങാം (Start Challenge) 🚀"** moves the player to the game screen.

---

### 2. Gameplay Screen 🥄💧

This is where the actual uselessness begins.

The gameplay interface contains:

- Animated spoon
- Animated water stream
- SVG bottle
- Multiple leakage streams
- Water level indicator
- Spoon counter
- Hole counter
- Time counter
- Remaining time
- Total leaked water
- Current water inside the bottle
- Add Water button
- Stop button

The gameplay interface is responsive and changes from a two-column layout to a single-column layout on smaller screens. 2

---

### 3. End Result Screen 📊

Once the player:

- Fills the bottle,
- Runs out of time, or
- Manually stops,

the game displays a final result.

The result includes:

- Time spent
- Number of spoons used
- Final number of holes
- Total water poured
- Total water leaked
- Water remaining in the bottle
- A randomly determined/funny player title
- A humorous message

---

# 💧 Game Mechanics

## Bottle Capacity

The virtual bottle has a maximum capacity of:

**500 ml**

```javascript
const MAX_CAPACITY = 500;
