# ccolor
Single-header color libary for C port from Qix-/color

Not sure if anyone do this or not but here is it.

Example: 
```c

RGB(15,23,45).rgb2hsl() // use h, s, l
RGB(15,23,45).hsl2rgb() // convert back
RGB(15,23,45).rgb2hsv() // use h, s, v
RGB(15,23,45).hsv2rgb() // convert back

RGB(15,23,45).luminosity()
RGB(15,23,45).contrast(RGB(15,23,45))
RGB(15,23,45).level() // return 1 or 2 or 3
RGB(15,23,45).isDark()
RGB(15,23,45).isLight()
RGB(15,23,45).negate() // return negate color
RGB(15,23,45).lighten(ratio) // return new color

... more is comming
```
