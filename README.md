# pi
円周率、こっちの方が安定してうまくいく

import numpy as np
from numpy.random import * 
import math
import matplotlib.pyplot as plt
N=1000
num=0
for i in range (N):
    x=rand()
    y=rand()
    #plt.plot(x,y,"bo")   
    if (x*x)+(y*y) < 1 :
    
        num+=1
num=4*num

print(num/1000)
plt.plot(x,y)
