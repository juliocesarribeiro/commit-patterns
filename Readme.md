  <h1 align="center">Padrões de Commits</h1>
  <p align="center">
    <a href="#git">Git</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
    <a href="#tipos-commits">Tipos de Commits</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
    <a href="#emojis">Emojis</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  </p>
  <br>
  <p align="center">
    <img alt="Git" src="https://upload.wikimedia.org/wikipedia/commons/e/e0/Git-logo.svg" width="20%">
  </p>

  <h2>🤔 O que é Git ?</h2>
  <p>
    Git é um sistema de controle de versão distribuído que permite que vários desenvolvedores trabalhem no mesmo projeto
    simultaneamente, sem que as alterações entrem em conflito.
  </p>
  <h2 id="git">🚀 Git</h2>
  <p>
    Esse documento foi criado utilizando a seguinte tecnologia.
  </p>
  <p>- Git</p>
  <p> - GitHub</p>
  <h2 id="tipos-commits">🧑🏻‍💻 Tipos de Commits</h2>
  <p>
    O commit possui os elementos estruturais abaixo (tipos), que informam a intenção do seu commit ao utilizador(a) de
    seu código.
  </p>
  <style>
    table {
      font-family: arial, sans-serif;
      border-collapse: collapse;
      width: 100%;
    }

    td,
    th {
      border: 1px solid #dddddd;
      text-align: left;
      padding: 8px;
    }

    tr:nth-child(even) {
      background-color: #dddddd;
    }

  </style>

  <table>
    <tr>
      <th>Estrutura</th>
      <th>Descrição</th>
    </tr>
    <tr>
      <td><strong>fix</strong></td>
      <td>Commits do tipo fix indicam que seu trecho de código commitado está solucionando um problema (bug fix).</td>
    </tr>
    <tr>
      <td><strong>feat</strong></td>
      <td>Commits do tipo feat indicam que seu trecho de código está incluindo um novo recurso ou uma nova funcionalidade.</td>
    </tr>
    <tr>
      <td><strong>docs</strong></td>
      <td>Commits do tipo docs indicam que houveram mudanças na documentação do projeto, como por exemplo no Readme do seu repositório.</td>
    </tr>
    <tr>
      <td><strong>style</strong></td>
      <td>Commits do tipo style indicam que houveram alterações referentes a formatações de código, semicolons, trailing spaces, css.</td>
    </tr>
    <tr>
      <td><strong>refactor</strong></td>
      <td>Commits do tipo refactor referem-se a mudanças devido a refatorações que não alterem sua funcionalidade, como por exemplo, uma alteração no formato como é processada determinada parte da tela, mas que manteve a mesma funcionalidade, ou melhorias de performance devido a um code review.</td>
    </tr>
    <tr>
      <td><strong>build</strong></td>
      <td>Commits do tipo build são utilizados quando são realizadas modificações em arquivos de build e dependências.
      </td>
    </tr>
    <tr>
      <td><strong>test</strong></td>
      <td>Commits do tipo test são utilizados quando são realizadas alterações em testes, seja criando, alterando ou excluindo testes unitários. 
      </td>
    </tr>
    <tr>
      <td><strong>chore</strong></td>
      <td>Commits do tipo chore indicam atualizações de tarefas de build, configurações de administrador, pacotes... como por exemplo adicionar um pacote no .gitignore.
      </td>
    </tr>
  </table>

  <h2 id="emojis">😅 Emojis</h2>
  <table>
    <tr>
      <th>Tipo de commit</th>
      <th>Emojis</th>
    </tr>
    <tr>
      <td><strong>Commit inicial</strong></td>
      <td>🎉 :tada:</td>
    </tr>
    <tr>
      <td><strong>Tag de versão</strong></td>
      <td>🔖 :bookmark:</td>
    </tr>
    <tr>
      <td><strong>Novo recurso</strong></td>
      <td>✨ :sparkles:</td>
    </tr>
    <tr>
      <td><strong>Lista de ideias (tasks)</strong></td>
      <td>🔜 :soon:</td>
    </tr>
    <tr>
      <td><strong>Bugfix</strong></td>
      <td>🐛 :bug:</td>
    </tr>
    <tr>
      <td><strong>Documentação</strong></td>
      <td>📚 :books:</td>
    </tr>
    <tr>
      <td><strong>Testes</strong></td>
      <td>🧪 :test_tube:
      </td>
    </tr>
    <tr>
      <td><strong>Adicionando um teste</strong></td>
      <td> ✅ :white_check_mark:
      </td>
    </tr>
    <tr>
      <td><strong>Teste de aprovação</strong></td>
      <td>✔️ :heavy_check_mark:
      </td>
    </tr>
    <tr>
      <td><strong>Acessibilidade</strong></td>
      <td>♿ :wheelchair:
      </td>
    </tr>
    <tr>
      <td><strong>Texto</strong></td>
      <td>📝 :pencil:
      </td>
    </tr>
    <tr>
      <td><strong>Package.json em JS</strong></td>
      <td>📦 :package:
      </td>
    </tr>
    <tr>
      <td><strong>Em progresso</strong></td>
      <td>🚧 :construction:
      </td>
    </tr>
    <tr>
      <td><strong>Arquivos de configuração</strong></td>
      <td>🔧 :wrench:
      </td>
    </tr>
    <tr>
      <td><strong>Removendo uma dependência</strong></td>
      <td>➖ :heavy_minus_sign:
      </td>
    </tr>
    <tr>
      <td><strong>Adicionando uma dependência</strong></td>
      <td>➕ :heavy_plus_sign:
      </td>
    </tr>
    <tr>
      <td><strong>Revertendo mudanças</strong></td>
      <td>💥 :boom:
      </td>
    </tr>
    <tr>
      <td><strong>Alterações de revisão de código</strong></td>
      <td>👌 :ok_hand:
      </td>
    </tr>
    <tr>
      <td><strong>Refatoração</strong></td>
      <td>♻️ :recycle:
      </td>
    </tr>
    <tr>
      <td><strong>Mover/Renomear</strong></td>
      <td>🚚 :truck:
      </td>
    </tr>
  </table>

  <h2>Exemplo de utilização</h2>
  <p>git commit -m ":tada: Iniciando projeto"</p>
  <p>git commit -m ":heavy_plus_sign: build: Instalando dependencias"</p>
  <p>git commit -m ":sparkles: feat(header): Adicionado e posicionado os icones"</p>
  <p>git commit -m ":books docs(readme): Criando documentação do projeto"</p>
