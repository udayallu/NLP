# NLP
## SequenceMatcher in difflib python library

```
import difflib

a = 'Thanks for calling America Expansion'
b = 'Thanks for calling American Express'

seq = difflib.SequenceMatcher(None,a,b)
d = seq.ratio()*100
print(d) 
# OUTPUT: 87.323943
````
