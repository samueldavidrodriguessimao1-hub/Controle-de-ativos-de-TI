# Controle-de-ativos-de-TI
ativos = []

def adicionar_ativo(nome, tipo):
    ativo = {"nome": nome, "tipo": tipo}
    ativos.append(ativo)

def listar_ativos():
    for a in ativos:
        print(f"Nome: {a['nome']} | Tipo: {a['tipo']}")

# Teste
adicionar_ativo("Notebook Dell", "Hardware")
adicionar_ativo("Windows 11", "Software")

listar_ativos()
