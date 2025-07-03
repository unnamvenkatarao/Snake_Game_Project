# **bold** ![Picture2](https://github.com/user-attachments/assets/1eb65469-0221-48b3-9ed4-1fb367227676) Snake Game – Java AWT/Swing
## 📌 Project Overview
This project is a classic Snake Game developed using the Java programming language and Java Frames (AWT/Swing) for the graphical user interface. It demonstrates the use of:

Object-Oriented Programming (OOP)

Event Handling

Real-Time Rendering

Basic Game Loop Logic using javax.swing.Timer

## 🎯 Objective
Control a snake on a 2D grid and guide it to eat food items.

Each time the snake eats food, it grows in length.

The game ends if the snake collides with itself or the boundaries of the screen.

## 🖥️ Setup
🪟 Game Window: 600x600 pixels square

🐍 Starting Position: Snake starts at the center of the screen

🍎 Food: Randomly appears on the grid

## 🎮 Gameplay Mechanics
▶️ Snake Movement
The snake moves continuously in the last direction set by the player.

Arrow Keys to control:

↑ UP

↓ DOWN

← LEFT

→ RIGHT

Edge Wrapping: If the snake moves off one edge, it appears on the opposite side (optional classic mode).

## 🍎 Eating Food
Food items appear randomly as dark blue circles.

When the snake’s head touches food:

The food is consumed.

The snake grows by one segment.

The score increases.

## 📈 Growing and Scoring
Each food item increases the length of the snake.

The score increases as the snake grows.

Game speed can be increased for additional challenge.

## ☠️ Game Over Conditions
The game ends when:

❌ The snake collides with itself.

❌ The snake hits the boundary (if wrapping is disabled).

## 🎨 Visuals & User Interaction
🎨 Color Scheme
Snake: 🟡 Light Yellow

Food: 🔵 Dark Blue

## 🧑‍💻 Controls
Controlled via keyboard arrow keys

Real-time input handling

Smooth gameplay with responsive movement

## 🛠️ Installation & Run Instructions
### ✅ Requirements
Java JDK (version 8 or higher)

Eclipse IDE (or any Java IDE)

## 🚀 Running the Game in Eclipse
Clone the Repository

bash
Copy
Edit
git clone https://github.com/unnamvenkatarao/Snake_Game_Project
Import into Eclipse

Open Eclipse

Go to File → Import → General → Existing Projects into Workspace

Browse to the cloned project folder and click Finish

Build and Run

Right-click on Game.java

Choose Run As → Java Application

💡 Ensure all .java files are in the src folder and within the same package if used.

## 🔮 Future Improvements
Add sound effects and background music

Introduce game levels with increasing difficulty

Add obstacles or traps on the grid

Implement a high-score leaderboard

Add pause/resume and restart options

## 📷 Preview
### Game Start:

![intial](https://github.com/user-attachments/assets/89dd10d4-5139-474d-acef-bb26da028dae)


### Game At Middle:

![Third](https://github.com/user-attachments/assets/8b91ead4-efa8-4f9a-b496-f69c6a4c8ca2)
<br>
![fourth](https://github.com/user-attachments/assets/f310b6a5-4b32-491c-a8e7-5a0ff64550ef)


### Game Over: 

![fiveth](https://github.com/user-attachments/assets/19bcc3ec-c03b-49cf-b17f-daac3fda645b)




## 🧾 License
This project is open-source and available for learning and improvement.
Feel free to fork, modify, and contribute!

