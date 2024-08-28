# Para mim, projetos web legais têm:

## Linguagem
Typescript, com strict mode, proibição de anys, detecção de nulos e paths alias.

## IDE
O vscode que é meu editor/IDE preferido, ele deve estar configurado e o projeto deve ter um .vscode integrando ESLint com o Prettier, e com regras adotadas no projeto. O output do Vscode deve estar sem erros.

## Linting
Para mim, o eslint deve estar configurado e sempre tendo evoluções, as regras devem ajudar a diminuir apontamentos em code reviews, detectar bugs e problemas, de forma sempre a otimizar a produtividade. Quando o ESLint começa a agilizar o desenvolvimento, para mim, esse é o momento em que o objetivo máximo do ESLint foi alcançado.

## Para testes unitários.
Para min, é fundamental ter ferramentas de testes configuradas, como Jest, React Testing Library, Vitest e com cobertura integrada

## Para testes e2e
Para testes e2e atualmente eu tenho mais experiência no Cypress e gosto muito de usar essa ferramenta no dia a dia, criando intercepts e até encontrando bugs usando diretamente o Cypress, sem precisar de recriar cenários mirabolantes e complexos em produção.

## Paixões
Sou apaixonado pelo processo de linting, sempre fico feliz quando minhas aplicações chegam a um nível onde o linting começa a evitar dores de cabeças. Para mim, esse é o ponto perfeito do linting, aquele em que você agradece o seu eu do passado por configurar essa ferramenta maravilhosa, também é onde a produtividade começa a aumentar de forma significativa.

Também é muito satisfatório quando testes quebram devido a um erro que cometi e não tinha percebido, isso faz a gente agradecer por criar aquele teste.

## Docker
Ter ambiente de dev, de testes e um make file são fundamentais para ter ambientes locais robustos, no frontend nem tanto, mas em backends complexos é fundamental. Eu gosto muito de configurar tudo e criar os atalhos no Makefile.

## Cultura
Valorizo muito a cultura de criticar sempre, de mexer no código alheio e de não ter medo de mexer no código que não é seu, gosto muito de não ter essas fronteiras, para min isso garante o desenvolvimento saudável de qualquer aplicação.

## Banco de dados
Atualmente eu gosto bastante de usar o mongodb, deve ser porque a maioria dos projetos mais recentes meus fazia sentido usá-lo.

## Framework de estilização
O tailwindcss atualmente é meu framework css preferido, ele traz os poderes do css de uma forma muito simples e dinâmica, e de cara ajuda a evitar important, combinando perfeitamente com frameworks modernos como react

## Sistema operacional
Atualmente uso muito o Ubuntu, é meu sistema favorito há anos e nunca me deixou na mão, além de trazer a melhor experiência para desenvolvimento web sem concorrentes na minha experiência.

## Framework frontend
Atualmente o Nextjs e Vite são as minhas ferramentas preferidas de frontend, permitindo criarmos frontends estáveis, bonitos, eficientes e otimizados e de uma forma bem simples.

## Boas práticas
Acho fundamental seguir boas práticas, como não usar abreviações, manter padrões de escrita, manter padrões de formatação, tendo um prettier integrado ao ESLint e atuando continuamente, e resolvendo os problemas sozinhos ao salvar as mudanças com o CTRL+S. 
Também acho fundamental evitar códigos complexos, profundos, mágicos, etc. (existem dezenas ou centenas de boas práticas, e algumas podem não ser boas práticas em certos contextos.)

## Pré-Commit
O projeto deve estar com commit lint, husk e ferramentas similares para detectar vulnerabilidades, rodar os testes, verificar se o commit está no padrão, etc.

## CICD
Uma pipeline completa de cicd com o gcp ou github actions, com testes e linting já é muito produtiva.

É um bônus se a pipeline tiver um pré-build, criação de tags, releases, preenchimento de prs já, teste de acessibilidade, integração com coverage, deploy de storybook, criação de ambientes dinâmicos, etc. Existe um mundo em CICD, o básico já é bom, mas tem como ir bem além do básico.

## Deploy
Uma coisa que gosto muito é a possibilidade de revert rápidos, como o que o argocd permite, eu ainda não sei configurar, mas é uma feature que é extremamente util e valiosa para manter a aplicação estável.

## Observabilidade
Em um frontend, para min é preciso ter pelo menos o Sentry configurado, observando não apenas erros na aplicação, mas erros nas requests também, e conectadas a canais como slack, Telegram ou e-mail. Isso nos permite descobrir quando um problema começa desde a primeira request com problema, isso já abre caminhos para uma investigação e uma correção, muitas vezes antes de ter qualquer report de incidente.

Para um backend, para min é fundamental termos os logs da aplicação, de forma simples, clara, com informações uteis, sem contaminação e de uma forma que até algum leigo possa entender, isso nos permite criar métricas, dashboards, alertas e até queries de anomalias, onde você cria uma quey que dispara alertas caso surja qualquer log novo (anomalia).

Com um ambiente dessa forma, o frontend e o backend estão continuamente vivos e reportando quando acontece qualquer coisa estranha, isso nos permite detectar scans, regressões do projeto ou externas, criar dashboards de fluxo de produto e muito mais.

## Toque de realidade
Logicamente, nem sempre tem como ter tudo isso, e às vezes temos que deixar algumas coisas de lado, mas faz parte, o importante é nunca se acomodar, e sempre voltar para resolver os problemas.

Além disso, essas são algumas preferências minhas quando escrevi esse texto. As coisas mudam e faz parte, eu entendo e mudo junto conforme a necessidade.
