# Reece Kramer
I was born in Iowa in 1997. I have a deep interest in video games and story telling. I am always tired.
![This Is me](me.jpg)
---
###### Sports you Should Try
Here are some Sport I think you should try.
| Baseball | Football | Basketball|
| Baseball Field| Football Field| Basketball Court|
| $1200 | $1100 | $100 |
---
###### Favorite Quotes
> I survived because the fire inside me burned brighter than the fire around me *Joshua Graham*
>
> I dont know any actual quotes *Reece Kramer*

---
###### Code
'''
long long binpow(long long a, long long b) {
    if (b == 0)
        return 1;
    long long res = binpow(a, b / 2);
    if (b % 2)
        return res * res * a;
    else
        return res * res;
}
'''
