# ativ-de-python-3


from modulo_calculadora import somar, subtrair, multiplicar, dividir

print(somar(2, 3))
print(subtrair(5, 2))
print(multiplicar(4, 3))
print(dividir(10, 2))
print(dividir(10, 0))


definição conversor_temperatura(Celsius):
    retornar(Celsius * 9 / 5)+ 32
definição validar_senha(senha):
    tem_tamanho_minimo = len(senha)>= 8
    tem_letra_maiuscula = qualquer(caractere.é superior()para caractere em senha)
    tem_letra_minúscula = qualquer(caractere.é menor()para caractere em senha)
    tem_numero = qualquer(caractere.é um dígito()para caractere em senha)
    retornar(
        tem_tamanho_minimo
        e tem_letra_maiuscula
        e tem_letra_minúscula
        e tem_numero
    )
definição caixa(*preços):
    retornar soma(preços)
definição aluno(**dados):
    retornar dados


    de módulo_utilidades importar caixa,conversor_temperatura,aluno,validar_senha
imprimir(f"25 recibo Celsius ={conversor_temperatura(25)}"Fahrenheit")
imprimir(f"Senha valida:{validar_senha('Senha123')}")
imprimir(f"Total da caixa: R${caixa(10,5,2,50):.2f}")
imprimir(f"Ficha do aluno:{aluno(nome='Ana',idade=20,curso='Python')}")




definição adicionar_item_seguro(lista,item):
	nova_lista = lista.cópia()
	nova_lista.acrescentar(item)
	retornar nova_lista




  de modulo_lista importar adicionar_item_seguro
lista_original =["arroz","feijao"]
lista_nova = adicionar_item_seguro(lista_original,"macaro")
imprimir(f"Lista original:{lista_original}")
imprimir(f"Lista nova:{lista_nova}")




de módulo_calculadora importar dividir,multiplicador,subtrair,somar
de módulo_utilidades importar caixa,conversor_temperatura,aluno,validar_senha
de lista importar adicionar_item_seguro
imprimir("Calculadora")
imprimir(f"Soma:{somar(2,3)}")
imprimir(f"Subtração:{subtrair(5,2)}")
imprimir(f"Multiplicação:{multiplicador(4,3)}")
imprimir(f"Divisão:{dividir(10,2)}")
imprimir(f"Divisão por zero:{dividir(10,0)}")
imprimir("\nUtilidades")
imprimir(f"25 recibo Celsius ={conversor_temperatura(25)}"Fahrenheit")
imprimir(f"Senha valida:{validar_senha('Senha123')}")
imprimir(f"Total da caixa: R${caixa(10,5,2,50):.2f}")
imprimir(f"Ficha do aluno:{aluno(nome='Ana',idade=20,curso='Python')}")
