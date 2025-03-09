// SimpleNumberGuessingGame.java

import java.util.Random;
import java.util.Scanner;

public class SimpleNumberGuessingGame {

    public static void main(String[] args) {
        Random random = new Random();
        int randomNumber = random.nextInt(100) + 1; // Generate a number between 1 and 100
        int attempts = 0;
        Scanner scanner = new Scanner(System.in);
        int guess;

        System.out.println("Welcome to the Number Guessing Game!");
        System.out.println("I've chosen a number between 1 and 100. Try to guess it.");

        while (true) {
            System.out.print("Enter your guess: ");
            guess = scanner.nextInt();
            attempts++;

            if (guess < randomNumber) {
                System.out.println("Too low! Try again.");
            } else if (guess > randomNumber) {
                System.out.println("Too high! Try again.");
            } else {
                System.out.println("Congratulations! You guessed the number in " + attempts + " attempts.");
                break;
            }
        }

        scanner.close();
    }
}
