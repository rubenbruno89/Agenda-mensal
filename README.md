
# Agenda Mensal com Tarefas Imprimível

## Descrição
Este projeto é uma **agenda mensal interativa** desenvolvida em HTML, CSS e JavaScript, que permite ao usuário visualizar e adicionar tarefas para cada dia do mês. A agenda pode ser facilmente navegada entre os meses e inclui uma opção para imprimir o layout com as tarefas adicionadas, ideal para organizar compromissos e atividades.

## Funcionalidades
- **Navegação Mensal**: Visualize e alterne entre meses com botões para o mês anterior e o próximo.
- **Adição de Tarefas**: Clique em qualquer dia do mês para adicionar tarefas personalizadas.
- **Marcação de Tarefas**: Clique em uma tarefa para marcá-la como concluída (linha riscada) e clique novamente para desfazer.
- **Impressão**: Inclui um botão de impressão que ajusta o layout da página, removendo elementos desnecessários para uma impressão limpa.

## Estrutura do Projeto
- **HTML/CSS**: Interface com layout responsivo, cores agradáveis e design amigável para visualização mensal.
- **JavaScript**: Scripts para controlar a navegação entre os meses, adicionar tarefas a cada dia e permitir impressão do calendário.

## Como Usar
1. Abra o arquivo `index.html` em um navegador.
2. Navegue entre os meses usando os botões **"< Mês Anterior"** e **"Próximo Mês >"**.
3. Para adicionar uma tarefa, clique em qualquer dia e digite a tarefa no prompt exibido.
4. Clique em uma tarefa para riscar como concluída e clique novamente para desfazer.
5. Para imprimir, clique no botão **"Imprimir Agenda"** na parte inferior.

## Estrutura do Código
- **updateCalendar()**: Renderiza o calendário do mês selecionado e cria elementos de interface para cada dia.
- **addTask()**: Função que permite adicionar tarefas em cada dia com uma interface simples de prompt.
- **print media query**: Estilos CSS específicos para otimizar o layout de impressão, ocultando botões de navegação e outros elementos.

## Licença
Este projeto está licenciado sob a licença MIT.

## Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir uma issue ou enviar um pull request.
