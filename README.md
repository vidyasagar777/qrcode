import qrcode #pip install qrcode
x = input("Enter your Data to create QR code: ")
img = qrcode.make(x)
y = input("Enter your Desired File name: ") 
img.save(y + ".jpg") #image saves
img.show() #image shows in figure window
