#  Minehead Food Festival
## April 2023


![20230419_080235](pics/20230419_080235.jpg)
![20230419_080248](pics/20230419_080248.jpg)
![20230419_080311](pics/20230419_080311.jpg)
![20230419_080349](pics/20230419_080349.jpg)
![20230419_080415](pics/20230419_080415.jpg)
![20230419_080457](pics/20230419_080457.jpg)
![20230419_080533](pics/20230419_080533.jpg)
![20230419_080602](pics/20230419_080602.jpg)
![20230419_080637](pics/20230419_080637.jpg)
![20230419_080713](pics/20230419_080713.jpg)
![20230419_080748](pics/20230419_080748.jpg)

###

Creating markdown format links:

```
ls pics |% {
    $b = $_.basename;
    $n = $_.name;
    "![$b](pics/$n)"
}
```
