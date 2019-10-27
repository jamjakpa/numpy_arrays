```python
import numpy as np
```


```python
mylist = [1,2,3]
```


```python
type(mylist)
```




    list




```python
myarray = np.array(mylist)
```


```python
myarray
```




    array([1, 2, 3])




```python
type(myarray)
```




    numpy.ndarray



now we transformed a normal python list into a numpy array



```python
np.arange(0,10,2)
```




    array([0, 2, 4, 6, 8])




```python
np.zeros(shape=(5,5))
```




    array([[0., 0., 0., 0., 0.],
           [0., 0., 0., 0., 0.],
           [0., 0., 0., 0., 0.],
           [0., 0., 0., 0., 0.],
           [0., 0., 0., 0., 0.]])



height and width 5 x 5


```python
type(0)
```




    int




```python
np.ones(shape=(2,4))
```




    array([[1., 1., 1., 1.],
           [1., 1., 1., 1.]])




```python

```


```python

```


```python

```


```python

```

BELOW SHOWING 10 RANDOM NUMBERS BETWEEN 0 - 100


```python
np.random.seed(101)
arr = np.random.randint(0,100,10)
```


```python
arr
```




    array([95, 11, 81, 70, 63, 87, 75,  9, 77, 40])




```python
arr2 = np.random.randint(0,100,10)
```


```python
arr2
```




    array([ 4, 63, 40, 60, 92, 64,  5, 12, 93, 40])



FINDING MAX in the Array


```python
arr.max()
```




    95



FINDING ( INDEX place ) MAX VALUE IN THE ARRAY 


```python
arr.argmax()
```




    0



FINDING MIN Value in Array


```python
arr.min()
```




    9



FINDING ( INDEX place ) MIN VALUE IN THE ARRAY



```python
arr.argmin()
```




    7



FINDING AVERAGE VALUE THE MEAN


```python
arr.mean()
```




    60.8



RESHAPING ARRAY IS SOMETIMES USEFULL


```python
arr.reshape((5,2))
```




    array([[95, 11],
           [81, 70],
           [63, 87],
           [75,  9],
           [77, 40]])




```python

```
