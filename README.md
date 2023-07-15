# bibliotecaCACHE
BIBLIOTECA VIRTUAL DESENVOLVIDA EM CACHÉ OBJECT SCRIPT
- COMPLETO-
=======================================================================================================
Essa Rotina foi desenvolvida como um aprendizado, estarei sempre buscando melhorá-la e qualquer crítica irá me ajudar a melhorar
o código para deixá-lo mais limpo e mais funcional para os usuários.

Me chamo Rodolfo Pitondo Solera e estou começando nesse maravilhoso Mundo ObjectScript, meu sonho é me tornar um
desenvolvedor e trabalhar com o que amo.
Espero que gostem do meu primeiro trabalho, é um trabalho simples porém, estarei me aperfeicoando cada vez mais nesse Mundo.

Caso queira o meu contato para conhecer mais sobre mim, ou me dar dicas e conselhos, será sempre bem-vindo.

Whatsapp: (47)99635-2197

Obrigado!
=======================================================================================================
Essas Rotinas contém:
^YYRPSBIB001:
MENU PRINCIPAL:
- RESERVAR LIVROS
- CONSULTAR RESERVAS
- CADASTRAR CLIENTES
- CADASTRAR AUTORES
- CADASTRAR LIVROS
- CADASTRAR GÊNEROS
- CADASTRAR EDITORAS

^YYRPSRES001:
RESERVAR LIVROS:
Ao entrar na Rotina, o sistema irá gerar o código da reserva automaticamente,
responsável por guardar as informações das reservas.
Sempre que acessar essa rotina, o número gerado será o próximo da reserva anterior.
A rotina permite que o mesmo cliente reserve vários livros, desde que o livro não esteja
em nenhuma outra reserva ou que a situação dessa reserva esteja como "ENTREGUE".
Irá ser necessário fornecer o código do livro, o código do cliente e quantos dias irá reservá-lo.
Após inserir esses dados, o sistema irá salvar essa reserva, informar o cliente a data que deverá ser entregue o livro
e a situação da reserva se tornará "EM ABERTO" até que o funcionário vá até a Consulta de Reservas e marque como "ENTREGUE".
OBS: Caso não tenha o código do cliente ou o código do livro, irá abrir a opção para consultar esses dados, exibindo os nomes
dos clientes e os nomes dos livros de acordo com o código do cadastro dos mesmos.

CONSULTAR RESERVAS:
Ao entrar na Rotina, o sistema irá pedir para que insira o código da reserva cadastrado, se o código não existir ele irá
lhe informar e retornará ao MENU INICIAL.
Caso insira um código existente, ele irá exibir os dados dessa reserva:
- Código da Reserva
- Nome do Cliente
- Nome do Livro
- Data da Entrega
- Situração da Reserva: "EM ATRASO", "ENTREGUE" ou "EM ABERTO"
E irá exibir opções para o usuário:
- Entregar o Livro:
Entrega o livro e fecha a reserva em aberto.
*OBS: APÓS ENTREGUE, A RESERVA NÃO PODERÁ SER MAIS ALTERADA!
- Prorrogar reserva:
Oferece a possibilidade do cliente aumentar a quantidade de dias que irá permanecer com o livro.
- Cadastrar nova reserva:
Encaminha o usuário a tela de criação de novas reservas.
- Retornar ao Menu Inicial:
Retorna o MENU INICIAL.

^YYRPSCLI001:
Ao acessar a Rotina, o usuário poderá cadastrar um novo Cliente. Da mesma forma da reserva, irá ser gerado um código automático
que irá respeitar sempre o próximo código após um existente.
OBS* Contém validação de Data de Nascimento: Usuário não pode ser menor de 16 anos ou maior de 99.
OBS2* Apenas CPF válidos são permitidos, e caso o CPF cadastrado já esteja em outro registro, o sistema irá informar e barrar essa ação.

^YYRPSAUT001:
Ao acessar a Rotina, o usuário poderá cadastrar um novo Autor que irá pertencer a um livro. Da mesma forma das anteriores,
irá ser gerado um código automático que irá respeitar sempre o próximo código após um existente.

^YYRPSGEN001:
Ao acessar a Rotina, o usuário poderá cadastrar um novo Gênero que irá pertencer a um livro. Da mesma forma das anteriores,
irá ser gerado um código automático que irá respeitar sempre o próximo código após um existente.

^YYRPSEDT001:
Ao acessar a Rotina, o usuário poderá cadastrar uma nova Editora que irá pertencer a um livro. Da mesma forma das anteriores,
irá ser gerado um código automático que irá respeitar sempre o próximo código após um existente.

^YYRPSLIV001:
Ao acessar a Rotina, o usuário poderá cadastrar um novo livro. Da mesma forma das anteriores, irá ser gerado um código
automático que irá respeitar sempre o próximo código após um existente.
Esse cadastro irá ser necessário informar o código do Autor do Livro, o código do Gênero do Livro e também o Código da Editora
do Livro.
Caso não saiba os códigos de qualquer um desses, irá ter a opção para visualizar os códigos existentes, apresentando sempre
o código seguido da descrição dos mesmos.

----------------------------------------------------------------------------------------------------------------------------


