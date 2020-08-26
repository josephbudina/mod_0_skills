class:

`Table`

Attributes:
```
table_type(string)
height(int)
has_candle(boolean)
party_guests(array)
```

Methods:
```
ask(interpolates table_type into new string)
stabilize(decreases height so that all legs are of equal length)
add_candle(turns return value of has_candle from false to true)
cancelation(one guest can't make it, so party_guests array decreases one element)
```
