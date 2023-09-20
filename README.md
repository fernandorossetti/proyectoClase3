nombre = input("Ingrese su nombre: ")
edad = int(input("Ingrese edad: "))

def pedido(**kwargs):
    refrigerio = {"pancho_grande":1000,"pancho_chico":700,"coca_chica":750,"coca_grande":1000}
    total = 0
    for i in kwargs:
        total =
if edad >=18:
    print("Tienes acceso al bar")
    tarjeta_vip = input("Tenes la vip?")
    valor_entrada = 5000
    if tarjeta_vip == "si":
        valor_descuento = valor_entrada -(valor_entrada*0.2)
        print("tenes 20% de descuento, vos pagas $", valor_descuento )
    elif tarjeta_vip == "no":
        print("No sos fiel al bar, recibis un caramelo nomas, te perdiste del descuento del 20 porciento, son $",valor_entrada)
elif edad <=17 and edad >14:
        print("No podes entrar, pero podes ingresar a la matiné")
        entrada_matine = 2000
        me_interesa = input("la entrada es de 2000, La queres?:")
        if me_interesa =="si":
            quiere_refrigerio = input("si compran un pancho y una coca, tienen un descuento del 3% de la entrada")
            if quiere_refrigerio == "si":
                valor_matine_descuento = entrada_matine -(entrada_matine*0.03)
                print("los precios son los
print("los precios son los siguientes:","Pancho chico",refrigerio.get("pancho_chico"),"pancho grande",refrigerio.get("pancho_grande"),"coca chica",refrigerio.get("coca_chica"),"coca grande",refrigerio.get("coca_grande"))
                combo_chico= input("cuantos combos chicos?")
                combo_grande = input("cuantos combos grandes?")
                minuta = {"combo_chico":0,"combo_grande":0}
                minuta["combo_chico"]=combo_chico
                minuta["combo_grande"] = com
