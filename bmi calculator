from tkinter import *
import tkinter
window = Tk()
window.title("BMI Calculator")
window.minsize(50,50)

def button_clicked():
    height= height_input.get()
    weight= weight_input.get()
    if weight == "" or height == "" :
        result_label.config(text= "Enter both weight and height")
    else:
        bmi = float(weight) / ((float(height) / 100) ** 2)
        result_label.config(text=f"Your bmi: {bmi}")


height= Label(text="Enter your weight(cm)")
height.config(bg="white",fg="black")
height.pack()
height_input = tkinter.Entry(width=10)
height_input.pack()



weight= Label(text="Enter your height (kg)")
weight.config(bg="white",fg="black")
weight.pack()
weight_input = tkinter.Entry(width=10)
weight_input.pack()

#text= Text(width=30)
#text.pack()

button = Button(text="Calculate",command=button_clicked)
button.pack()

result_label = tkinter.Label()
result_label.pack()



window.mainloop()
