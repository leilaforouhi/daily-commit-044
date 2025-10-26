def replace_word(text, old, neW):
    return text.replace(old, new)

if __name__ == "__main__":
    sample = "GitHub daily commits are fun"
    old = "fun"
    new = "productive"
    print(f"Updated text: {replace_word(sample, old, new)}")

