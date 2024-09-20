# Diário da Colina - Newsletter Fictícia

Este projeto foi desenvolvido com o objetivo de aprender a criar uma mensagem de e-mail usando apenas HTML e CSS puro. Foi um desafio interessante, pois os clientes de e-mail geralmente não suportam as tecnologias mais recentes do CSS. Por isso, foi necessário utilizar tabelas para estruturar o layout, da mesma forma que os sites eram construídos no passado, além de tags como `<center>` e estilos como `text-align:center` para alinhar os elementos.

Outro ponto importante é que, devido à limitação de suporte às atualizações mais recentes do CSS por parte dos clientes de e-mail, também foi necessário utilizar o **CSS inline** para aplicar estilos diretamente nos elementos, garantindo que o layout fosse renderizado corretamente em diversos serviços de e-mail.

## Tecnologias Utilizadas
- **HTML**
- **CSS (Inline)**

## Desafios do Projeto
Os principais desafios envolvem a compatibilidade entre clientes de e-mail, já que muitos não suportam as funcionalidades modernas do CSS. Por isso, precisei adotar técnicas mais antigas, como o uso de tabelas para layout e alinhamento de conteúdo, além de aplicar os estilos diretamente nos elementos via **CSS inline**.

## Imagens
Para garantir uma boa performance e carregamento rápido, todas as imagens usadas no e-mail foram comprimidas utilizando o [ILoveIMG](https://www.iloveimg.com/pt/comprimir-imagem). O repositório de imagens está hospedado no meu GitHub, e pode ser acessado no link:

- [Repositório de Arquivos Estáticos - GitHub](https://github.com/inacio-developer/static_files)

## Testes de Compatibilidade
O e-mail foi testado usando o serviço [Putsmail](https://putsmail.com/), que permite verificar se o e-mail renderiza corretamente em diferentes clientes de e-mail. Todas as mensagens passaram nos testes com sucesso.

## Tema: Vasco da Gama - Notícias
O tema da newsletter fictícia é chamado **Diário da Colina**, um boletim que cobre notícias relacionadas ao Vasco da Gama. Para as notícias, foram utilizados três artigos do Globo Esporte:

1. **Vasco e Vegetti abrem conversas para renovação do contrato**  
   Escrito por Tébaro Schmidt  
   [Leia o artigo completo](https://ge.globo.com/futebol/times/vasco/noticia/2024/09/19/vasco-e-vegetti-abrem-conversas-para-renovacao-do-contrato.ghtml)

2. **Enquete: quase 80% da torcida do Vasco prefere jogo contra o Atlético-MG em São Januário**  
   Escrito pela Redação GE  
   [Leia o artigo completo](https://ge.globo.com/futebol/times/vasco/noticia/2024/09/19/em-enquete-quase-80percent-da-torcida-do-vasco-prefere-jogo-contra-o-atletico-mg-em-sao-januario.ghtml)

3. **O que Felipe faz no Vasco? Entenda os bastidores do trabalho do diretor técnico**  
   Escrito por Tébaro Schmidt  
   [Leia o artigo completo](https://ge.globo.com/futebol/times/vasco/noticia/2024/09/19/o-que-felipe-faz-no-vasco-entenda-os-bastidores-do-trabalho-do-diretor-tecnico.ghtml)

## Como Testar o Projeto
Você pode visualizar e testar o e-mail da seguinte maneira:
1. Copie o código HTML do arquivo `index.html`.
2. Acesse o site [Putsmail](https://putsmail.com/).
3. Cole o código HTML na área de envio e adicione o seu e-mail como destinatário.
4. Envie o e-mail para testar sua aparência diretamente em sua caixa de entrada.

## Como Visualizar o Projeto
1. Clone este repositório:
   ```bash
   git clone https://github.com/inacio-developer/seu-projeto.git

2. Abra o arquivo index.html diretamente no navegador para visualizar o layout do e-mail.
   
## Licença
Este projeto foi feito para fins educacionais e não está sob nenhuma licença específica. As notícias foram usadas como exemplo, e todos os direitos sobre os textos são reservados aos seus respectivos autores e veículos de comunicação.

Espero que este projeto possa servir como inspiração para a criação de e-mails eficientes e responsivos, levando em consideração as limitações e peculiaridades de renderização nos clientes de e-mail.
