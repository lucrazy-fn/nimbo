# Nimbo

Um espaço visual para organizar a rotina, estudar melhor e transformar planos em próximos passos.

## Sobre o projeto

O Nimbo foi criado para juntar planejamento pessoal, estudos e foco em uma experiência leve e agradável. A interface combina uma atmosfera azul céu, clima dinâmico, animações suaves e ferramentas editáveis para acompanhar o dia sem deixar tudo pesado.

## Recursos

1. Rotina diária com horários, duração, categorias, dias da semana e checklist.
2. Visão semanal para acompanhar o ritmo dos próximos dias.
3. Editor completo para criar, editar e excluir atividades.
4. Anexos de imagens e links de apoio nas atividades.
5. Progresso diário e tempo intencional concluído.
6. Tela de abertura personalizada com nome, horário, temperatura e condição do céu.
7. Tema claro e tema escuro com identidade visual própria.
8. Mapa mental com múltiplos mapas, ideias, imagens, links e conexões curvas.
9. Modo para mover ideias e modo separado para redimensionar os cards.
10. Linhas suaves, retas ou tracejadas com opção de animação.
11. Área de estudos com timer de foco, notas escolares, cartões de revisão e biblioteca de referências.
12. Guias e sites personalizados organizados por assunto.
13. Som ambiente gerado localmente com controle de reprodução, volume e silêncio.
14. Personalizações salvas automaticamente no navegador.

## Preset inicial

O projeto começa com uma rotina editável inspirada no plano 2027:

1. Escola das 06:00 às 12:50.
2. Almoço e descanso.
3. Estudos.
4. Treino de xadrez.
5. Exercício físico.
6. Partidas rapid diárias.
7. Análise das partidas.
8. Programação por 30 minutos.
9. Inglês por 30 minutos.
10. Lazer.
11. Sono às 21:00.

## Como executar

Abra o arquivo `index.html` no navegador.

Também é possível publicar a pasta como um site estático no GitHub Pages, Netlify, Vercel ou qualquer serviço compatível com HTML, CSS e JavaScript puros.

O projeto não precisa de instalação, banco de dados ou etapa de build.

## Estrutura

1. `index.html` contém a estrutura das telas e componentes.
2. `styles.css` contém a identidade visual, os efeitos e o layout responsivo.
3. `app.js` contém a rotina, o mapa mental, o estúdio, o clima, o áudio e a persistência local.
4. `logo.svg` contém a marca visual do Nimbo.

## Privacidade

As personalizações ficam no `localStorage` do navegador. O som é sintetizado localmente com Web Audio API e não depende de faixas protegidas por direitos autorais.

## Sincronização entre dispositivos

Na área de Configurações, crie uma conta ou entre com seu e-mail e senha. Use a mesma conta no computador e no celular para sincronizar a rotina, os estudos, os mapas mentais e as preferências.

O modo local continua disponível quando a pessoa não estiver conectada. Os dados da conta ficam protegidos por políticas de acesso individuais no Supabase.

## Publicação

O repositório de teste está disponível em [github.com/lucrazy-fn/nimbo](https://github.com/lucrazy-fn/nimbo).

Quando o GitHub Pages estiver ativado, a aplicação poderá ser acessada em [lucrazy-fn.github.io/nimbo](https://lucrazy-fn.github.io/nimbo/).

