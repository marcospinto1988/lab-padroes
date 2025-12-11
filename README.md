# lab-padroes

# Documentacao do modulo de Conexão

## Descrição
este projeto implenta um padrão de conexão segura com o banco de dados, utilizando **Design Patterns** para evitar *hardcoding*.

## O que foi feito
- [x] Criação do repositorio
- [x] Implementação da conexão
- [x] Resolução de conflito de Merge
- [x] Separação de configuração

## Exemplo do Uso
Abaixo, o codigo padrão utilizado pelo Arquiteto:

```pyton
# Constante de configuração
DB_HOST = "192.168.0.1"

def conectar_banco():
   """conect usando a constante definita"""
   return f"Conectado ao {DB_HOST}"
