# Counting
This program will take the name of a file as a parameter to `main()`, open it, read its contents, then output: a word count, the longest word, and the average word length.

## Requirements
- The program will not take input from the keyboard.
- Words will be split by any character in the following string: `" \t\n\r.!?,"`
- Words will have both ends stripped of the following characters: ``"!?,.-:;'()[]{}@#$%^&*_+=/<>`~ \"\t\n\r"``
  - If one of these characters appears in the middle of the word, like the apostrophe in a word like "don't", it will be left alone.
  - Numbers, or words containing digits, shall not be counted.
  - Empty strings must not be counted.
- The word count is a whole number.
- The longest word must be enclosed in double-quation marks.
- The average word length must always show one decimal place.
- Input files are provided, including the two that will be used to grade.

## Sample Runs
This run uses the file `input.FIRST`
```
❯ ./a.out input.FIRST
There were 3 words read.
The longest word is "cat"
The average word length is 3.0 letters.
```

This run uses the file `input.HERBERT` (Attribution: Frank Herbert)  
```
❯ ./a.out input.HERBERT
There were 61 words read.
The longest word is "little-death"
The average word length is 3.9 letters.
```

## Hints
- You will want to utilize the entire week.
- Remember the "proper etiquette" around file streams.
- While no functions are required, it would be silly to not use any.
- Create your own test cases where word counts and averages are easy to calculate by hand and verify.
- Not knowing the size of the inputs ahead of time should rule out static storage.
- Familiarize yourself with `<string>` and `<vector>`.
  - https://en.cppreference.com/w/cpp/string/basic_string
  - https://en.cppreference.com/w/cpp/container/vector
- Familiarizing yourself with other libraries we've covered in class can also be beneficial.

## Reminders
- Submit **only** your source code.
- Name your file *wsuid*\_hw08.cpp
- You are required to place a comment block at the top of the file. Refer to the Coding Guidelines
handout.
