# dio-miniguia-estudos-notebooklm
Um minirepositório para reportar as atividades realizadas no desafio de projeto da DIO "Treinando uma IA de Aprendizagem: Explore o Poder do NotebookLM"

## Contexto e Objetivos
Com o aumento no interesse de hobbies analógicos, uma demanda por RPGs de mesa, ou TTRPGs, está em alta; e para que qualquer um possa participar desse hobby mais facilmente, foi-se criado um NotebookLM para poder estudar com facilidade as regras básicas do jogo Dungeons & Dragons 5ª Edição. O objetivo é aprender o básico do jogo para poder jogar ou para mestrar sua própria sessão.

## Curadoria de Fontes
- https://media.wizards.com/2018/dnd/downloads/DnD_BasicRules_2018.pdf (PDF das regras básicas do jogo)
- https://www.dndbeyond.com/sources/dnd/basic-rules-2014 (regras básicas do jogo no site D&D Beyond)
- https://www.dndbeyond.com/sources/dnd/mcv1/spelljammer-creatures (opções alternativas para NPCs)
- https://www.dndbeyond.com/sources/dnd/sac/sage-advice-compendium (erratas e solução de dúvidas frequentes)

## Engenharia de Prompts e "Cicatrizes"
Algumas das perguntas feitas:
- *"Eu nunca ouvi falar de RPG. Pode me dar um review básico?"*
- *"Quero jogar. Por onde eu começo?"*
- *"Nunca ouvi falar de D&D. Poderia me dar os principais pontos-chave para eu entender?"*
- *"Vou ser um jogador! O que devo saber para criar um personagem?"*
- *"Tenho meu personagem! E agora, como eu aprendo a jogar?"*
Houve dificuldades para a plataforma explicar em PT-BR visto que o material base está em inglês. Outros materiais como relatórios e vídeos só saem em inglês.

## Miniguia de Estudo (Entrega Final)
### 1. Resumos Estruturados do Assunto
O jogo é dividido em três grandes pilares: Exploração, Interação Social e Combate. Tudo é movido pela imaginação e mediado por regras e dados.

#### A. A Regra de Ouro: O Teste de d20
O fluxo básico do jogo segue este ciclo: o Mestre descreve o ambiente, os jogadores dizem o que querem fazer e o Mestre narra os resultados. Quando o resultado é incerto, faz-se um teste:
- Rolar um d20.
- Adicionar o Modificador de Atributo (ex: Força, Destreza).
- Adicionar o Bônus de Proficiência (se o personagem for treinado na tarefa).
- Comparar com um Número Alvo: Se o total for igual ou superior à Classe de Dificuldade (DC) ou à Classe de Armadura (AC), a ação é um sucesso.

#### B. Atributos e Modificadores
Existem seis habilidades básicas que definem cada criatura:
- *Força*: Poder físico e atletismo.
- *Destreza*: Agilidade, reflexos e equilíbrio.
- *Constituição*: Saúde e resistência (afeta os Pontos de Vida).
- *Inteligência*: Memória e raciocínio lógico.
- *Sabedoria*: Percepção e intuição.
- *Carisma*: Influência social e força de personalidade.

#### C. Criação de Personagem em Passos
- *Escolha uma Raça*: Define traços naturais como visão no escuro ou bônus em atributos.
- *Escolha uma Classe*: Define sua profissão heroica (Guerreiro, Mago, Clérigo ou Ladino) e seus poderes principais.
- *Determine Atributos*: Use o conjunto padrão (15, 14, 13, 12, 10, 8) ou role dados.
- *Descreva o Personagem*: Escolha um nome, alinhamento moral e um Antecedente (o que você fazia antes de ser herói).
- *Equipamento*: Obtenha itens iniciais baseados na classe e antecedente.

#### D. O Sistema de Magia
- *Espaços de Magia (Slots)*: Funcionam como munição. Magias de nível 1 ou superior consomem esses espaços.
- *Truques (Cantrips)*: Magias de nível 0 que podem ser lançadas à vontade, sem gastar espaços.
- *Componentes*: Podem ser Verbais (palavras mágicas), Somáticos (gestos) ou Materiais (itens específicos).
- *Concentração*: Algumas magias exigem foco contínuo. Se você sofrer dano ou lançar outra magia de concentração, a anterior pode acabar.

### 2. Glossário de Conceitos Principais
- **AC (Armor Class / Classe de Armadura)**: O número alvo para alguém conseguir te atingir em combate.
- **DC (Difficulty Class / Classe de Dificuldade)**: O número alvo para ter sucesso em um teste de habilidade ou salvaguarda.
- **Vantagem/Desvantagem**: Em vantagem, role dois d20 e use o maior. Em desvantagem, use o menor.
- **Iniciativa**: Um teste de Destreza no início do combate para definir a ordem dos turnos.
- **Salvaguarda (Saving Throw)**: Um teste forçado para resistir a um efeito negativo, como um feitiço ou veneno.
- **Bônus de Proficiência**: Um bônus fixo (começa em +2 no nível 1) aplicado a tudo que seu personagem "sabe fazer bem".
- **Descanso Curto (Short Rest)**: Pausa de pelo menos 1 hora para recuperar vida usando Dados de Vida.
- **Descanso Longo (Long Rest)**: Pausa de 8 horas que recupera toda a vida e espaços de magia.

### 3. Prompts Reutilizáveis para Revisão
Você pode usar estes prompts para explorar os documentos com a IA em futuras sessões de estudo:
- **Para Regras Específicas**: *"Com base nas fontes, explique detalhadamente como funciona a mecânica de [inserir regra, ex: Combate Montado ou Cobertura] e quais são os bônus/penalidades aplicados."*
- **Para Criação de Personagem**: *"Me ajude a construir um [inserir classe] de nível 1. Sugira a melhor distribuição para o conjunto padrão de atributos (15, 14, 13, 12, 10, 8) e explique quais perícias eu ganho com o antecedente [inserir antecedente]."*
- **Para Dúvidas Técnicas (Sage Advice)**: "Como a regra [inserir regra] interage com [inserir outra regra ou magia] de acordo com o Sage Advice Compendium?"*
- **Para Mestres (DMs)**: *"Crie um encontro de combate de dificuldade 'Média' para um grupo de 4 personagens de nível 3, utilizando monstros da lista de Challenge Rating das fontes."*
- **Para Simulação de Jogo**: *"Descreva uma cena de exploração em uma masmorra e peça para eu realizar um teste de habilidade relevante, narrando o resultado com base no que eu rolar."*
