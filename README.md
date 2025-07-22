probleme1
ALGORITHME somme_element
var
// Array declaration
A ,B : array
i,j : intiger
Sum: intiger

begin
sum=0


/ Enter elements
for i from 0 to length (A)-1 do
if A[i] is not in B then
sum=sum+ A[i]
end if

 
end for


for j from 0 to length(B)- 1 do
  if B[j] is not in A then
  sum= sum + B[j]
  end if
end for
whrite sum " la somme est :"



end for
end
.................................................................
probleme2

procedure dot_product (v1,v2,ps)
v1:array
v2: array
  for each pair (v1, v2)  in the list of vectors do
  if dot_product (v1 ,v2)  =0
  then   
whrite " les vecteurs v1 et v2 sont orthogonux"
else 
whrite " les vecteurs v1 et v2 ne sont pas orthogonux
end if
end for
end






.........................
fonction dot_product (v1,v2) :intiger
var 
v1,v2: array
ps : intiger
i: intiger

begin
for i from 1 to length(v1) do
ps = ps +v1[i] * v2[i]
end for
retun ps
end
