Input handling:

- The program prompts the user to enter an 11-digit identification number using Scanner.
- The input is read as a long to handle large numbers without losing precision.
  
Year extraction:

- The extractYear method converts the number to a string, checks its length to ensure it's 11 digits, and extracts the first two digits to represent the year.
- If the input does not meet the length requirement, an IllegalArgumentException is thrown.
  
Main method:

- The main method reads the input from the user, calls the extractYear method, and prints the extracted year.
