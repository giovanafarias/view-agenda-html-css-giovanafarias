📒 Atividade: Criando Telas para o Sistema de Agenda e Contatos
🎯 Objetivo
Nesta atividade, você irá praticar HTML e CSS construindo as telas de Index e Cadastro de Contatos para um sistema de Agenda.
Ainda não vamos integrar com o Javalin (isso será feito nas próximas aulas). O foco aqui é treinar a estruturação das páginas e a aplicação dos conceitos de estilização em CSS.

📌 Contexto do Projeto
Estamos criando um Sistema de Agenda e Contatos.
No backend (Java), temos dois modelos principais:

// Classe Agenda
public class Agenda {
    private String descricao;
    private String tipo;
    ...
}

// Classe Contato
public class Contato {
    private String nome;
    private String email;
    private String telefone;
    ...
}
🚀 Por enquanto, sua missão é:
Criar a tela Index (Home), onde será apresentada a agenda de contatos.
Criar a tela Cadastro de Contatos, com um formulário para inserir:
Nome
E-mail
Telefone
🖼️ Telas a Desenvolver
1. Index (Home)
Um título com o nome do sistema: "Agenda de Contatos"
Uma lista (simulada) de contatos já cadastrados.
Um botão/link para a tela de cadastro.
2. Cadastro de Contatos
Um formulário com os campos:
Nome (input text)
E-mail (input email)
Telefone (input tel)
Botão para "Cadastrar" (por enquanto não precisa funcionar).
Um link para voltar à página inicial (Index).
🎨 Estilização com CSS
Você deve aplicar CSS externo para:

Definir fontes, cores e espaçamento.
Organizar os elementos na tela (pode usar
Tornar a interface mais amigável e clara.
💡 Dica: Aproveite para explorar:

Pseudo-classes (:hover, :focus)
Classes reutilizáveis para botões, inputs etc.
Organização em arquivo separado (style.css).
📂 Estrutura de Arquivos Sugerida
/projeto-agenda
│── index.html
│── cadastro.html
│── /css
└──────style.css
🚀 Próximos Passos nas Aulas
Nas próximas aulas, vamos:

Integrar o HTML com o Javalin (Java).
Utilizar o template engine Freemarker para dar vida às telas, permitindo que os dados de contatos e agendas sejam exibidos dinamicamente.
Aprender a criar rotas no Javalin que vão conectar o backend com as telas criadas aqui.
Ou seja: hoje criamos a "fachada" (HTML + CSS), e em breve daremos vida ao sistema conectando frontend e backend. 🎉

✅ Entrega
Suba os arquivos no repositório.
Certifique-se de que o HTML esteja semântico e o CSS bem organizado.
Na próxima aula, vamos integrar essas telas com o Javalin + Freemarker para funcionar dinamicamente.
