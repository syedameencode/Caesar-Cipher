# Caesar Cipher (Python)

A simple command-line tool to encrypt and decrypt text using the classic Caesar cipher.

## Features
- Encode/decode with custom positive/negative shifts
- Preserves punctuation, numbers, and spaces
- Case-aware with A–Z wrap-around
- Input validation and helpful prompts

## Usage
python caesar.py
# Choose encode/decode, enter your message, provide shift

# (Optional CLI style)
python caesar.py --mode encode --text "hello world" --shift 5

## Project Structure
- caesar.py  # main logic
- helpers.py # (optional) utility functions

## Learnings
- String manipulation, ord/chr, modular design, basic cryptography

## Future Improvements
- File input/output
- Frequency analysis (breaking cipher without a key)
- Simple GUI / web UI
