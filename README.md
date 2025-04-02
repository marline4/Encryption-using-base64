# Encryption-using-base64
import base64

def encrypt_pass(password):
    encoded_bytes = base64.b64encode(password.encode())
    print(encoded_bytes)
name= input("Enter your name: ")
print("Welcome to WHTA networks, " + name +"" )
user_name= input ("Kindly input your preferred username")
print("Ah! that is an interesting name, " + user_name + "!")
user_pass = input("Enter Your password: ")
encrypt_pass(user_pass)
print("That is your encrypted password we will be decrypting it soon. See you soon 🤗")
