def primo(num):
    if num<2:
        return False
    for i in range(2,int(num**0.5)+1):
        if num % i == 0:
            return False
    return True
def gerar(qnt):
    primos = []
    n = 2
    while len(primos)< qnt:
        if primo(n):
            primos.append(n)
        n += 1
    return primos
primos = gerar(100)
print(primos)
