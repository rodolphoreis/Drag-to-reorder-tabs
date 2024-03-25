# Framer Motion: drag to reorder tabs

## Descrição

Este projeto demonstra como implementar funcionalidade de arrastar e reordenar para abas usando Framer Motion 10.17.0. Os usuários podem interagir com as abas arrastando-as para reordenar ou clicando para selecioná-las. Quando uma aba é removida, a próxima aba na lista é selecionada automaticamente. Além disso, novas abas podem ser adicionadas até um limite predefinido.

## Instalação

Para executar o projeto localmente, certifique-se de ter o Node.js instalado. Em seguida, siga estas etapas:

1. Clone o repositório do GitHub.
2. Navegue até o diretório do projeto.
3. Execute `npm install` para instalar as dependências.
4. Execute `npm start` para iniciar o servidor de desenvolvimento.

## Uso

O projeto consiste em um componente principal `App` localizado em `src/App.tsx`. Este componente gerencia as abas e sua funcionalidade. As abas são representadas pelo componente `Tab` localizado em `src/Tab.tsx`.

### Componentes

#### Componente Tab

O componente `Tab` representa abas individuais na interface. Ele consiste nas seguintes propriedades:

- `item`: Um objeto que representa o conteúdo da aba (ícone e rótulo).
- `isSelected`: Um booleano que indica se a aba está atualmente selecionada.
- `onClick`: Uma função para lidar com a seleção da aba.
- `onRemove`: Uma função para lidar com a remoção da aba.

#### Componente AddIcon

O componente `AddIcon` representa o ícone para adicionar novas abas.

#### Componente CloseIcon

O componente `CloseIcon` representa o ícone para remover abas.

### Funcionalidade

- As abas podem ser arrastadas para reordená-las.
- Clicar em uma aba a seleciona.
- Clicar no ícone de fechar remove a aba.

## Dependências

- `framer-motion`: "^10.17.0"
- `react`: "^18.2.0"
- `react-dom`: "^18.2.0"
- `react-scripts`: "^4.0.3"

## Dependências de Desenvolvimento

- `@types/react`: "^17.0.20"
- `@types/react-dom`: "^17.0.9"
- `typescript`: "^4.4.2"

## Scripts

- `npm start`: Inicia o servidor de desenvolvimento.
- `npm build`: Compila o projeto para produção.
- `npm test`: Executa testes usando Jest.
- `npm eject`: Ejeta o projeto do Create React App.

## Suporte de Navegador

O projeto é testado e suportado em navegadores modernos, excluindo Internet Explorer 11 e Opera Mini.

---

Para mais detalhes, consulte o código-fonte e a documentação.

