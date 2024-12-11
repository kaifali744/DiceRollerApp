# DiceRollerApp 🎲  

DiceRollerApp is a simple Android application built in Kotlin to simulate a dice roll. On pressing the "Roll" button, the app generates a random number (1–6) and displays a dice image corresponding to the rolled number. This project was created to practice random number generation, using `when` statements, and dynamically updating an `ImageView` in Android.

## Features  
- **Random Number Generation**: Simulates a dice roll by generating a random number between 1 and 6.  
- **Dynamic Image Updates**: Each number is mapped to a corresponding dice image, which is displayed in an `ImageView`.  
- **Interactive UI**: Includes a "Roll" button that updates the dice image based on the rolled number.  
- **Efficient Logic**: Utilizes the `rollDice()` function and a `when` statement to manage image selection.

## Technologies Used  
- **Kotlin**: Programming language for building the app.  
- **Android Studio**: IDE for Android development.  
- **ImageView**: For displaying dice images.  
- **Button**: For user interaction to roll the dice.

## How It Works  
1. The "Roll" button triggers the `rollDice()` function.  
2. The function generates a random number between 1 and 6 using the `Random` class.  
3. A `when` statement maps the generated number to its corresponding dice image resource.  
4. The selected image is then dynamically set to the `ImageView`.  



## Getting Started  
1. **Clone the Repository**:  
   ```bash  
   git clone https://github.com/kaifali744/DiceRollerApp.git  
