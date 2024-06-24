# Modelagem e Diagramação de um Componente iPhone - UML

```mermaid
classDiagram
class ReprodutorMusical {
    ReprodutorMusical : + tocar()
    ReprodutorMusical : + pausar()  
    ReprodutorMusical : + selecionarMusica(musica)
}
 
                      
class AparelhoTelefonico {
    AparelhoTelefonico : + ligar(numero) 
    AparelhoTelefonico : + atender() 
    AparelhoTelefonico : + iniciarCorreioVoz()
}
 

class NavegadorInternet {
    NavegadorInternet : + exibirPagina(url) 
    NavegadorInternet : + adicionarNovaAba()  
    NavegadorInternet : + atualizarPagina() 
}

 class iPhone {
    }

    iPhone --> ReprodutorMusical
    iPhone --> AparelhoTelefonico
    iPhone --> NavegadorInternet
```