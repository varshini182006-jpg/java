# java

# 🎮 Basic Text-Based Adventure Game

## 📌 Project Overview

The **Basic Text-Based Adventure Game** is an interactive Java-based adventure application that allows players to explore a fictional world, make decisions, and experience different story endings based on their choices.

The game is developed using Java AWT (Abstract Window Toolkit), providing a simple graphical interface with buttons for player interactions and a text area to display the storyline.

Players begin their adventure in a mysterious forest and can choose different paths, explore caves, cross rivers, discover hidden locations, and experience multiple endings.

This project demonstrates the practical implementation of Java programming concepts, including classes, objects, event handling, conditional statements, methods, and GUI development.

## 🎯 Objectives

- To develop an interactive adventure game using Java.
- To understand Java AWT and GUI development.
- To implement event-driven programming using ActionListener.
- To apply conditional statements and switch-case structures.
- To create multiple story paths based on player decisions.
- To improve logical thinking and problem-solving skills.

## ✨ Features

- **Interactive GUI:** Simple graphical interface developed using Java AWT.
- **Multiple Choices:** Players can select different actions using buttons.
- **Branching Storylines:** Different decisions lead to different story paths.
- **Multiple Endings:** Experience victory, safe endings, heroic endings, and game-over situations.
- **Event Handling:** Uses ActionListener to process player interactions.
- **Play Again Option:** Restart the adventure after completing a storyline.
- **Exit Option:** Close the game whenever required.
- **User-Friendly Interface:** Displays story descriptions and available choices clearly.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Java (JDK 21) | Core programming language |
| Java AWT | Graphical user interface |
| ActionListener | Handling button events |
| EventQueue | Managing GUI execution |
| Java Classes and Objects | Organizing game components |
| Switch-Case | Managing different game states |
| Conditional Statements | Processing player decisions |
| VS Code | Development environment |

## 🏗️ System Architecture

The game follows an event-driven architecture in which the player's button selection determines the next game state.

### Game Flowchart

```text
       ┌──────────────────────┐
       │     Start Game       │
       └──────────┬───────────┘
                  │
                  ▼
       ┌──────────────────────┐
       │ Display Welcome Page │
       └──────────┬───────────┘
                  │
                  ▼
       ┌──────────────────────┐
       │ Player Selects Path  │
       │   Left or Right      │
       └──────────┬───────────┘
                  │
          ┌───────┴────────┐
          ▼                ▼
    ┌───────────┐    ┌───────────┐
    │ Left Path │    │Right Path │
    └─────┬─────┘    └─────┬─────┘
          │                │
          ▼                ▼
    ┌───────────┐    ┌───────────┐
    │ River     │    │   Cave    │
    │ Adventure │    │ Adventure │
    └─────┬─────┘    └─────┬─────┘
          │                │
          ▼                ▼
    ┌───────────┐    ┌───────────┐
    │  Player   │    │  Player   │
    │  Choices  │    │  Choices  │
    └─────┬─────┘    └─────┬─────┘
          │                │
          └───────┬────────┘
                  │
                  ▼
       ┌──────────────────────┐
       │ Display Game Ending  │
       └──────────┬───────────┘
                  │
                  ▼
       ┌──────────────────────┐
       │  Play Again or Exit  │
       └──────────────────────┘
```

## 🎮 Gameplay Description

### 1. Start Game
The player starts the adventure in a mysterious forest and is presented with two choices:
- Left
- Right

### 2. Left Path – River Adventure

When the player selects the left path, they reach a river.

Available choices:
- **Swim:** Reach an island and explore further.
- **Build:** Attempt to build a raft.
- **Follow:** Follow the river and find a friendly fisherman's hut.

Further exploration provides additional choices such as exploring a shrine, resting, or returning.

### 3. Right Path – Cave Adventure

When the player selects the right path, they discover a mysterious cave.

Available choices:
- **Enter:** Enter the cave and encounter a sleeping dragon.
- **Back:** Return to the forest.
- **Wait:** Discover a secret entrance and a hermit's hut.

Inside the cave, players can fight the dragon, sneak past it, or retreat.

### 4. Multiple Endings

The game provides several possible endings depending on the player's decisions.

Examples include:
- Victory Ending
- Safe Ending
- Heroic Ending
- Lucky Ending
- Mystical Ending
- Grand Ending
- Game Over

### 5. Restart or Exit

After completing an adventure, players can choose:
- Play Again – Restart the game.
- Exit – Close the application.
## ⚙️ Installation and Execution

### Prerequisites

- Java Development Kit (JDK 21)
- Visual Studio Code or any Java-supported IDE
- Java Extension Pack (for VS Code)

### Step 1: Clone the Repository

```bash
git clone https://github.com/your-username/Basic-Text-Based-Adventure-Game.git
```

### Step 2: Navigate to the Project Folder

```bash
cd Basic-Text-Based-Adventure-Game
```

### Step 3: Compile the Java Program

```bash
javac AdventureAWT.java
```

### Step 4: Run the Application

```bash
java AdventureAWT
```

The adventure game window will open, allowing the player to start exploring the fictional world.

## 📸 Screenshots

Screenshots of the application demonstrate the different stages of gameplay.

### Home Page
<!-- Add Home Page Screenshot Here -->

### Left Path – River Adventure
<!-- Add Left Path Screenshot Here -->

### Swim Option
<!-- Add Swim Screenshot Here -->

### Rest Option
<!-- Add Rest Screenshot Here -->

### Wisdom Ending
<!-- Add Wisdom Screenshot Here -->

### Follow Option
<!-- Add Follow Screenshot Here -->

### Right Path – Cave Adventure
<!-- Add Right Path Screenshot Here -->

### Enter Cave
<!-- Add Enter Cave Screenshot Here -->

### Sneak Option
<!-- Add Sneak Screenshot Here -->

### Search Hut
<!-- Add Search Hut Screenshot Here -->

### Fight Dragon
<!-- Add Fight Dragon Screenshot Here -->

### Climb Tower
<!-- Add Climb Tower Screenshot Here -->

## 🚀 Future Enhancements

The project can be enhanced with the following features:

- **Inventory Management:** Allow players to collect and use different objects.
- **Character Statistics:** Introduce health, energy, strength, and experience points.
- **Advanced Storylines:** Add more locations, challenges, and multiple story paths.
- **Database Integration:** Store player details and game progress using MySQL.
- **Save and Load:** Allow players to save their adventure and continue later.
- **Improved GUI:** Develop a more attractive interface using Java Swing or JavaFX.
- **Sound Effects:** Add background music and sound effects.
- **Multiplayer Support:** Allow multiple players to participate in the adventure.

## 🎓 Learning Outcomes

Through this project, the following Java programming concepts are demonstrated:

1. Understanding Java classes and objects.
2. Implementing event-driven programming.
3. Working with Java AWT components.
4. Handling button click events using ActionListener.
5. Applying switch-case and conditional statements.
6. Managing game states and branching logic.
7. Using methods for modular programming.
8. Understanding GUI execution using EventQueue.

## 👩‍💻 Project Details

| Particulars | Details |
|---|---|
| Project Title | Basic Text-Based Adventure Game |
| Student Name | S. Varshini |
| Register Number | 8115U24EC119 |
| Course Code | EGB1201 – Java Programming |
| Department | Electronics and Communication Engineering |
| Institution | K. Ramakrishnan College of Engineering (Autonomous) |
| Programming Language | Java |
| JDK Version | JDK 21 |
| GUI Framework | Java AWT |
| Academic Year | 2025–2026 |

## 📚 References

1. Oracle – Java SE 21 Documentation: https://docs.oracle.com/en/java/javase/21/
2. Oracle – Java AWT API Documentation: https://docs.oracle.com/javase/8/docs/api/java/awt/package-summary.html
3. Oracle – Java Event Handling: https://docs.oracle.com/javase/tutorial/uiswing/events/
4. Introduction to Programming Using Java – David J. Eck.
5. Introduction to Java Programming and Data Structures – Y. Daniel Liang.
6. Head First Java – Kathy Sierra and Bert Bates.
7. Java How to Program – Paul Deitel and Harvey Deitel.
8. W3Schools – Java OOP Concepts: https://www.w3schools.com/java/java_oop.asp
9. Game Programming Patterns – Robert Nystrom.

## ⭐ Conclusion

The Basic Text-Based Adventure Game successfully demonstrates how Java programming concepts can be used to develop an interactive adventure application. Through Java AWT, event handling, conditional statements, and game-state management, the project provides an engaging experience where player decisions determine the progression of the storyline.

This project strengthens fundamental Java programming knowledge and provides a foundation for developing more advanced interactive games and applications.

---

**Developed as part of EGB1201 – Java Programming.**

**K. Ramakrishnan College of Engineering (Autonomous).**
