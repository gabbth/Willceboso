main.py

import tkinter as tk from tkinter Impo

import random

from tkinter import messagebox

root = tk. Tk()

root.title('Aceltas?')

rout.gioetry("600")

root.configure(background="#ffcBdd")

def move button 1(e):

(f abs(e.x-button 1.winfe_x())se and abs(e.y-button Lvinfo y()) < 40: random.randint(0, root.winfo width() button 1.winfo_width())

y-random.randint(e, root.winfo height()-button 1.winfo height())

button 1.place(xxx, y)

def accepted(): messagebox.showinfo(

def denied(): button 1.destroy()

margin Canvas(root, width-508; bg="#ffc@dd, height-100,

bda, highlightthickness-0, relief="ridge")

margin.pack()

test_id Label(root, by="effcadd", text-"Quer namorar comigo?",

fg-"#590422", font-('Montserrat, 24, 'bold')) test_Id.pack() button 1 tk.Button(sot, text="Não", bg="#ffb3c1', commodened,

rettof-RIDGE, 20-3, font-("Montserrat", "bold"))

button 1.pack()

root.bind("Motions, move button 1)

button 2 tk.Button(root, text-"Sim", bg-"affb3c1", relief-RIDGE,

bd-3, commie-a
