money = int(input('金額(円)を入力>'))
print('金額：',money,'円',sep='')

maisuu = money // 500
money = money % 500
print('五百円玉=',maisuu,'枚',sep=' ')
maisuu = money // 100
money = money % 100
print('百円玉　=',maisuu,'枚',sep=' ')
maisuu = money // 50
money = money % 50
print('五十円玉=',maisuu,'枚',sep=' ')
maisuu = money // 10
money = money % 10
print('十円玉　=',maisuu,'枚',sep=' ')
maisuu = money // 5
money = money % 5
print('五円玉　=',maisuu,'枚',sep=' ')
print('一円玉　=',money,'枚',sep=' ')
