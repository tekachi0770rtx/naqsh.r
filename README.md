# naqsh.r
this pattern
from turtle import *
import colorsys as cs
bgcolor('black')
tracer(10)
pensize(3)
h = 0

for i in range(210):
    c=cs.hsv_to_rgb(h,1,1)
    h+=0.01
    pencolor(c)
    begin_fill()
    lt(105)
    fd(200-i)
    circle(-30, -150)
    fd(200-i)
    circle(-30)
    end_fill()
done()
