# Repositório de exemplo
Afim de incluir um exemplo para o projeto final da disciplina APS.

![Imagem da documentação](https://raw.githubusercontent.com/lucas-althoff/Exemplo_Repo_APS/refs/heads/main/static/crew_pesquisa_futebol.png)


```mermaid
classDiagram
    note "From Duck till Zebra"
    Animal <|-- Duck
    note for Duck "can fly\ncan swim\ncan dive\ncan help in debugging"
    Animal <|-- Fish
    Animal <|-- Zebra
    Animal : +int age
    Animal : +String gender
    Animal: +isMammal()
    Animal: +mate()
    class Duck{
        +String beakColor
        +swim()
        +quack()
    }
    class Fish{
        -int sizeInFeet
        -canEat()
    }
    class Zebra{
        +bool is_wild
        +run()
    }
```

```python
def funcao_qualquer(arg1):
  print(Exemplo de uso do markdown com linguagem)
```

```shell
$ pip install meu_pacote
```
