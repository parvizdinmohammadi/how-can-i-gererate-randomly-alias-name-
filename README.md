# how-can-i-gererate-randomly-alias-name-in python?
import random

first_parts = ["Cyber", "Digital", "Neon", "Quantum", "Stealth", "Shadow", "Phantom", "Pixel"]
second_parts = ["Ninja", "Wolf", "Falcon", "Phoenix", "Ghost", "Viper", "Tiger", "Eagle"]

def random_alias():
    return f"{random.choice(first_parts)}{random.choice(second_parts)}"

print(random_alias())  # Example: "NeonPhoenix"
