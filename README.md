:spiral_calendar: Atualizado em 16 de agosto de 2021 :heart:

<img align="right" alt="GIF" height="160px" src="https://github.com/rdeconti/rdeconti-resources/blob/main/under_construction.gif" />

:blush: Este projeto está em estudo. Carga inicial realizada para manter cópia de segurança :blush:

<img align="right" alt="GIF" height="160px" src="https://github.com/rdeconti/rdeconti-resources/blob/main/Digital%20Innovation%20One%20-%20Logotipo.png" />

# Projeto Digital Innovation One - App Android KOTLIN para apresentar seu portfólio de projetos do GitHub 
Este projeto foi proposto pela Digital Innovation One
- Link do código original: 
- https://github.com/EzequielMessore/To-Do-List
- Professora: Ezequiel Messore
- Aula: https://web.digitalinnovation.one/lab/criando-um-app-de-lembretes-e-tarefas-com-kotlin/learning/8759e2e9-0a1b-49b6-b9fd-e32f3c79803e

##Descrição
Crie um App no estilo "To Do List" do zero e conduza todo o processo de desenvolvimento usando Kotlin, uma das linguagens de programação de maior ascensão nos últimos anos. Além disso, você é desafiado a evoluir o App e entregar uma solução ainda mais robusta.

##Descrição do projeto original
## Aulas e materiais de estudo.
- Aula - 01: Apresentação pessoal e apresentação do curso.
  - [Apresentação](https://drive.google.com/file/d/1KhneglCpya7VgAsczDsa7zXmpWkyo0XZ/view?usp=sharing)
- Aula - 02: Configurando nosso primeiro projeto.
- Aula - 03: Um pouco do Android Studio.
  - [Conheça o Android Studio](https://developer.android.com/studio/intro)
- Aula - 04: Temas
  - [Documentação dos temas](https://developer.android.com/guide/topics/ui/look-and-feel/themes?hl=pt-br)
  - Link de referência do [stackoverflow](https://stackoverflow.com/questions/22192291/how-to-change-the-status-bar-color-in-android/24997241#24997241)
  - Customização do Floating Action Button [stackoverflow](https://stackoverflow.com/questions/30969455/android-changing-floating-action-button-color/56158913#56158913)
- Aula - 05:  Começando por a mão na massa.
  - [Protótipo](https://xd.adobe.com/view/77c56d1f-232d-41e9-a220-371d51991646-2296/)
  - [Material Design](https://material.io/design)
- Aula - 06: Criando a tela criar tarefas.
- Aula - 07: ViewBinding e DatePicker.
  - [Documentação do View Binding](https://developer.android.com/topic/libraries/view-binding)
  - [Artigo sobre View Binding](https://medium.com/androiddevelopers/use-view-binding-to-replace-findviewbyid-c83942471fc)
- Aula - 08: Time Picker.
  - Problema com o TimeZone [stackoverflow](https://stackoverflow.com/a/60979837)
- Aula - 09: RecyclerView.
  - Documentação do [RecyclerView](https://developer.android.com/guide/topics/ui/layout/recyclerview?hl=pt-br).
- Aula - 10: Mostrando lista de tarefas.
  - [Popup menu](https://material.io/components/menus#usage)
- Aula - 11: Editando tarefas.
- Aula - 12: Finalizando o app.
   - [Empty States](https://material.io/design/communication/empty-states.html#content)


## Desafios
Tornar nosso aplicativo um aplicativo resiliente que não perca nossas tarefas salvas quando é encerrado, para isto podemos usar a estratégia de salvar nossos dados localmente.  
Podemos fazer isto de duas maneiras usar nossas [Shared Preferences](https://developer.android.com/training/data-storage/shared-preferences?hl=pt-br) ou nosso [SQLite](https://developer.android.com/training/data-storage/sqlite) para utilizar os esses conceitos de uma maneira facilitada devemos usar as seguintes bibliotecas:

 - [Room](https://developer.android.com/training/data-storage/room): é um banco de dados que oferece uma camada de abstração sobre o SQLite, e nos ajuda a lidar melhor com a complexidade do mesmo.

 - [DataStore](https://developer.android.com/topic/libraries/architecture/datastore?hl=pt-br): é uma solução de armazenamento de dados que permite armazenar pares de chave-valor ou objetos tipados.
