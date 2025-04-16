PoC: Jogo de Combinação de Receitas Brasileiras
Prova de Conceito (PoC) de um jogo de combinação estilo Candy Crush + 2048, onde o objetivo é combinar ingredientes para formar receitas típicas brasileiras.

🎯 Objetivo
Desenvolver um mínimo produto viável (MVP) para validar a mecânica principal do jogo:
✅ Combinação em duas etapas (3 ingredientes → 1 combinado; 2 combinados → receita)
✅ Grid interativo com movimentação por swipe (deslize)
✅ Sistema de pontuação baseado em combinações
✅ Visualização em tempo real com SpriteKit

🛠️ Tecnologias Utilizadas
Ferramenta	Por que escolhi?
-> SpriteKit	Framework nativo da Apple para jogos 2D, perfeito para manipulação de sprites, física e animações simples.
-> Swift	Linguagem principal para desenvolvimento iOS/macOS, com performance otimizada.
-> Combine	Para gerenciar estados reativos (ex: atualizar pontuação, grid) de forma elegante.

🧩 Mecânica Principal
🔄 Combinação em 2 Passos
-> Combine 3 ingredientes iguais (ex: 3 feijões) → vira um ingrediente combinado.
-> Combine 2 ingredientes combinados (ex: 1 combinado de feijão + 1 de farinha) → forma uma receita (ex: feijoada).

🏗️ Estrutura do Código
Copy
PoCGameSpriteKit/  
├── GameScene.swift       # Cena principal (grid, física, input)  
├── GameModel.swift       # Lógica do jogo (matriz, combinações)  
├── Ingredient.swift      # Classe base para ingredientes  
├── Recipe.swift          # Objeto de receita final  
└── (Assets/)             # Sprites (feijao.png, farinha.png, etc.)  
    
🚀 Como Executar
Copy
git clone https://github.com/seu-usuario/PoCGameSpriteKit.git
Abra no Xcode (PoCGameSpriteKit.xcodeproj).

Execute no simulador (⌘ + R).

📌 Próximos Passos 
-> Adicionar sons e animações ao combinar.
-> Implementar sistema de níveis com receitas diferentes.
-> Criar menu inicial com SwiftUI.

🤔 Por que Essas Tecnologias?
-> SpriteKit > Unity/Godot: Para uma PoC simples, evita overengineering e mantém tudo nativo.
-> Combine: Facilita o gerenciamento de estado reativo (ex: atualizar UI quando o score muda).
-> Matriz 4x4: Inspirado no 2048, mas adaptado para combinações temáticas.

📄 Licença
MIT License - Livre para uso e modificação.

Feito com ❤️ por Letícia Bezerra.

🔗 Aprendeu algo? Dá uma ⭐ no repositório!

📌 Dúvidas?
Abra uma issue ou me chame no Twitter/LinkedIn.

