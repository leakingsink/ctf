
```python
def sub_120A(a1):
    if ord(a1) <= 77: return ord(a1) + 181
    else: return ord(a1) + 177
a1 = 'BBBBBZBBBBBBBBAAAAAAAAAAAAOOOOOO'
v3 = 247
for j in range(1,32):
    v3 += sub_120A(a1[j]) - j + 247
print(v3)
print(v3%248)
```


```
BBBBBZBBBBBBBBAAAAAAAAAAAAOOOOOO
```
