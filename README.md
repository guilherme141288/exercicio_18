# exercicio_18
#randomly picking an item

from random import choices, choice
pri = str (input ('primeiro aluno: '))
seg = str (input ('segundo aluno: '))
ter = str (input ('terceiro aluno: '))
qua = str (input ('quarto aluno: '))
grp =  [pri , seg , ter , qua]
sort = choice (grp)
print ('o sorteado é {}' .format (sort))
