# Color
 print colorful strings in shell environment

# Usage

```julia
red("i am red") |> print

print(red("i am red"))

blue("i am so blue") |> print

print(blue("blue") * red("me") * "...")
```

You could specify foreground or background colors as
+ black
+ red
+ green
+ yellow
+ blue
+ magenta
+ cyan
+ white

For each color you can specify one mode, like
+ default
+ bold
+ underline
+ blink
+ swap
+ hide

For more flexibility, use :
```julia
color("yellow", "yellow on red"; background = "red", mode = "bold") |> print
```
