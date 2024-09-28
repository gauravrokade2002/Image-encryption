# PRODIGY_CS_02
Image Encryption 
#GAURAV MAHADU ROAKDE 
GUI interface or tool where the user can encrypt and decrypt an image via pixel manipulation, we'll use Python, specifically the tkinter library for the GUI and PIL (Python Imaging Library) for image processing. The key idea is to ensure that the image cannot be viewed correctly without the correct decryption key.

Steps to Implement:
1.	Setup the Environment:
	Install the required libraries:
		a. bash
		b. Copy code
		c. pip install tkinter pillow numpy
2.	Create the GUI Interface:
		The interface will allow users to select an image, enter an encryption key, and then encrypt or decrypt the image.
		Provide options to save the encrypted image.
3.	Encryption and Decryption Logic:
		We'll use a pixel manipulation technique, such as XOR with a key derived from the user's input, to ensure that the image can only be decrypted with the correct key.
		The encrypted image should look different from the original, and the original should be recoverable using the same key.
4.	Saving and Loading Images:
		Users can save the encrypted image and share it with others who can decrypt it using the same key and code.


Key Points:

•	Security: The XOR operation is simple and serves the purpose for basic encryption/decryption. For stronger security, more advanced algorithms can be used.
•	User Interface: The interface is straightforward, with options to load, encrypt, decrypt, and save images.
•	Key Handling: The encryption and decryption depend on the correct key being provided. An incorrect key will result in an unintelligible image.



STEPS:


1.	Opening the Image: Users can open an image from their file system, which will then be displayed in the GUI.
2.	Encryption Process: The image is encrypted by performing a pixel-wise XOR operation with the key. The result is an encrypted image that looks different from the original.
3.	Decryption Process: The same XOR operation is applied to the encrypted image with the same key to recover the original image.
4.	Saving the Encrypted Image: The encrypted image can be saved and shared. Only someone with the same key and the decryption code can recover the original image.
