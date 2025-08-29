1 ile 100 arasındaki asal sayıları listeleyen python programları
alt = 1 
ust = 100 
  
for sayi in range(alt,ust + 1):  
   if sayi > 1:  
       for i in range(2,sayi):  
           if (sayi % i) == 0:  
               break  
       else:  
           print(sayi)  
