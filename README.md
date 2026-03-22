total = 0
while True:
    valor = float(input('enter an expense'))
    if valor == 0:
        print('stopping...')
        break
    total += valor 

print('total expense:', total)

if total == 100:
    print('limit expense')
elif total > 100:
    print("you've crossed the limit")
elif total >70:
    print('high expense')
else:
    print ('within the limit')
