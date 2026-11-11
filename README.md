# KP-python-password-generator (Documentation)

A beginner Python project that generates random passwords.

##Concepts learned: 
* Functions
* The random module 
* For loops
* String module

# How it Works: 

1. The program prompts the user with "Password Length: " and takes a numeric input.
2. It calls generate_password(length) passing the requested length.
3. Inside generate_password(length), it creates a pool of characters using string.ascii_letters, string.digits, and string.punctuation.
4. It iterates length times, picking a random character from the pool using random.choice() and appending it to the password string.
5. Finally, the function returns the generated password, which is printed to the terminal. 

# Example Output
Enter Password Length: 12
k9#mP2!xL8$q
