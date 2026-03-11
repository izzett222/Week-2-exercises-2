# Exercise 1: Secret Message Decoder
A spy agency sends encoded messages where every character is **shifted forward by 2 letters in the alphabet**.

For example:
Encoded: jgnnq  
Original: hello

Your job is to **decode the message**.
### Tasks
1. Given a string: ex: String encoded = "jgnnq yqtnf";
2. Decode the message by shifting each letter **2 positions backward**.
3. Spaces should remain unchanged.
4. Print the decoded message

# Exercise 2: Caesar Cipher Decoder
You intercepted a coded message where every character was shifted **forward by 3 letters**.

Example:
- Encoded: khoor  
- Original: hello

### Tasks
1. Go through each character in the string.
2. If it is **not a space**(spaces remain the same), shift it **3 characters backward**
3. Build the decoded message.
4. Print the result.
    

### Expected Output
Encoded message: khoor zruog  
Decoded message: hello world  
Length: 11

# Exercise 3: Password Sanitizer
A website receives passwords with **extra spaces and inconsistent capitalization**.  Before storing them, the system must **clean and validate** the password.
### Ex: Given
String password = "   SeCrEt123   ";

### Tasks
1. Remove extra spaces.
2. Convert the password to **lowercase**.
3. Check:
    - if the password **starts with a letter**
    - if the password **contains a digit**
4. Print a formatted report.

### Expected Output
Original password : "   SeCrEt123   "  
Cleaned password  : "secret123"  
Length: 9  
Contains digit: true  
Starts with letter: true

# Exercice 4. Simple Chat Filter
A chat application must **filter offensive words** before displaying messages.

### Given
String message = "This game is stupid";
### Tasks
1. Check if the message **contains `"stupid"`**.
2. If it does:
    - replace `"stupid"` with `"***"`.
3. Convert the message to uppercase.
4. Print a formatted report.
5. (optional) support filtering of other offensive words
    
### Expected Output
Original message: This game is stupid  
Contains banned word: true  
Filtered message: THIS GAME IS ***  

# Exercise 5: Character Shift Puzzle
A strange keyboard shifts letters depending on their position in the word.
Rules:
- Characters at **even index** → shift **+1**
- Characters at **odd index** → shift **-1**
- Spaces stay the same.
### Tasks
1. Loop through the string.
2. If the character  is even → increase character by `1`.
3. If the character is odd → decrease character by `1`.
4. Build the new string.
5. Print the new string

# Exercises 6: Manual Word Counter
You are writing a **simple text editor** that must count the number of words.
### Rules
A **word** is any sequence of characters separated by spaces.
### Tasks
Write code that counts the number of words.
**Expected output:**
Text : Java is fun to learn  
Words: 5

### Twist (harder)
Make it work even if there are **multiple spaces**:
"Java   is   fun"

**Expected result:**
Words: 3


# Exercise 7: Chat Message Analyzer
### Given
String message = "  Java Programming Is Fun  ";
### Tasks
1. Remove spaces at the start and end.
2. Convert everything to **lowercase**.
3. Count:
    - number of **letters**
    - number of **spaces**
4. Print a report.
### Expected Output Example
Original message: "  Java Programming Is Fun  "  
Cleaned message: java programming is fun  
Letters: 20  
Spaces : 3  
Updated message: java programming is fun  
Length: 20
# Exercise 8: Simple Caesar Cipher Tool
You must write a tool that **encodes messages** by shifting letters.
Example shift **+1**:

hello → ifmmp

### Given
String message = "hello world";  
int shift = 3;

### Tasks
1. Loop through each character.
2. Shift letters forward by `shift`.
3. Leave spaces unchanged.
4. Print encoded message.
### Extra challenge
Make the alphabet **wrap around**:
z + 1 → a


# Exercise 9:  Multi-Rule Character Transformer
A strange encryption machine applies **three rules** to every character.
Rules:
1. **Letters**
    - even index → shift `+2`
    - odd index → shift `-1`
2. **Digits**
    - increase digit value by `1`
3. **Spaces**
    - replace with `_`
### Task
Write a program that applies all the rules and builds a new string.

# Exercise 10: Progressive Caesar Cipher
Instead of a fixed shift, each character is shifted **based on its position**.

**Rule:**
shift = index + 1

Example:

|index|shift|
|---|---|
|0|1|
|1|2|
|2|3|
|3|4|
### Task
Shift each character forward by `(index + 1)`.
**Note**: The character needs to wrap.

