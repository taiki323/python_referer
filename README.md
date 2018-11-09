# python_referer

h, w, n = [int(x) for x in input_lines.split(" ")]
print(' '.join(map(str,table[i])))

[[0] * 3 for x in range(2)] ⇒[[0, 0, 0], [0, 0, 0]]   

while True:   
    try:   
        input_lines = input()   
        print(input_lines)   
    except EOFError:   
        break   

リスト
list.append(a) #末尾にaを追加    
list.extend([a]) #末尾にaの要素を追加   
list = list + list  #extendと同じ    
list.insert(1,[1,2,3]) #インデックスを指定してオブジェクト追加    
del list[1]   
list.pop(1) #消されてたオブジェクトを返す    
list.remove("B") #指定した要素を消す    
1 in list #リスト内にあったらTrue    
list.index("B")    
list.count(1) #指定要素の数     

list.sort()    
list.reverse()    
    
numpy
np.zeros([2,2], dtype=int)
a.resape(-1)
np.sort(a)
np.append(a, 1)
np.insert(a,1,"A")

