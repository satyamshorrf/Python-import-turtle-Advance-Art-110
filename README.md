# Python-import-turtle-Advance-Art-110
Create python use import turtle graphics code
from turtle import*
from time import*
import colorsys as cs 
title("Satyam Shorrf")
bgcolor('black')
tracer(2)
sleep(2)
pensize(2)
h = 0
for i in range(16):
    for j in range(18):
        c = cs.hsv_to_rgb(h,1,1)
        color(c)
        h += 0.005
        goto(0,0)
        right(90)
        circle(150-i*6, 90)
        left(90)
        right(180)
    circle(40, 24) 
    hideturtle()
done()
       
