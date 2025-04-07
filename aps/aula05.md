# Organização Prática de Requisitos com Foco em Rastreabilidade

## 🎯 Objetivo
Organizar e refinar requisitos de forma prática e incremental, garantindo rastreabilidade, clareza e foco no que realmente é necessário.

**Classificação dos Requisitos:** 
- Funcionais vs. Não-funcionais
	- Um Cliente pode ter realizar Reservas.
	- A Reserva deve ser realizada em 20s.
- Requisitos do sistema vs. do usuário
	- O sistema deve ser compatível com as versões mais recentes dos navegadores Chrome, Firefox e Safari.
	- O Cliente deve ser capaz de acessar sua conta e visualizar suas reservas em até 30 segundos após abrir o aplicativo.
- Requisitos explícitos vs. implícitos
	- Um Cliente pode ter realizar Reservas.
	-  O Cliente espera que a reserva seja intuitiva e que as opções de menu sejam facilmente localizáveis. (Implícito, a usabilidade geralmente é dada como garantida, mas não é especificada).

→ Traga exemplos práticos para cada no seu diário.

## 📚 Fundamentos Teóricos Aplicados

### ✅ Rastreabilidade
- Permite ligar cada requisito a funcionalidades, testes, casos de uso, código, etc.
- Código identificador de requisitos.
- Conexão entre requisitos principais e específicos.

### ✅ Decomposição Funcional (Refinamento Incremental)
- Organização em fases.
- Macro para o micro com clareza - uma prática essencial em levantamento e análise de requisitos.
- Como? Quebra de requisitos em subníveis com detalhamento progressivo.
  
### ✅ Engajamento e Validação com Stakeholders
- Detalhar quem faz o quê (cliente, administrador) - simular papéis de usuários reais ajuda a validar requisitos com clareza.

### ✅ Separação de Escopo
- Inclusão explícita de funcionalidades não correlatas ao objetivo principal.

### ✅ Análise de Papéis (Stakeholders)
- Definição clara de clientes e administradores.

### ✅ Modularidade e Organização
- Agrupar os requisitos por fases e hierarquia melhora a modularidade, facilitando a análise de impacto e a evolução futura.
- Estrutura clara, hierárquica e didática.

### ✅ Qualidade dos Requisitos (SMART)
Ao refinar e detalhar, você aproxima os requisitos das boas práticas de qualidade:
- Específico: define quem faz o quê
- Mensurável: funcionalidades podem ser testadas
- Alcançável / Realista: não são utopias
- Temporal: implícito no calendário ou lembretes
- Rastreável: claramente mapeado do geral ao específico

### ✅ Análise de Completeness
- Ir da ideia inicial até requisitos complementares e fora do escopo, você conduz uma análise de completude.

---

# Exemplo

## 🧩 Estrutura das Fases

### 🔹 **Fase 1 – Identificação do Requisito Principal**
- [LRP001] Realizar a gestão de reserva de quadras esportivas de beach tennis e futebol society.

### 🔹 **Fase 2 – Especificação**
- [LRE001] Realizar a gestão de reserva de quadras de beach.
- [LRE002] Realizar a gestão de reserva de quadras de futebol society.

### 🔹 **Fase 3 – Especificação com Atores**
- [LRE001] Permitir que o cliente realize a gestão de reserva de quadras de beach.
- [LRE002] Permitir que o cliente realize a gestão de reserva de quadras de futebol society.
- [LRE003] Permitir que o administrador realize a gestão de todas as reservas de quadras de beach.
- [LRE004] Permitir que o administrador realize a gestão de todas as reservas de quadras de futebol society.

### 🔹 **Fase 4 – Complementação Funcional**
- [LRE005] Definir calendário para facilitar a visualização da disponibilidade das quadras.
- [LRE006] Definir um sistema de reserva inteligente em que um jogador possa definir um dia de jogo e o sistema realizar o convite para dar quórum.

### 🔹 **Fase 5 – Funcionalidades Fora do Escopo Inicial**
- [LRE007] Definir um controle de venda de refrigerantes.

---

### Resultado final
```
[LRP001] Realizar a gestão de reserva de quadras esportivas de beach tennis e futebol society.

	[LRE001] Permitir que o cliente realize a gestão de reserva de quadras de beach.
 
	[LRE002] Permitir que o cliente realize a gestão de reserva de quadras de futebol society.
 
	[LRE003] Permitir que o administrador realize a gestão de todas as reserva de quadras de beach.
 
	[LRE004] Permitir que o administrador realize a gestão de todas as reserva de quadras de futebol society.
 
	[LRE005] Definir calendário para facilitar a visualização da disponibilidade das quadras.
 
	[LRE006] Definir um sistema de reserva inteligente em que um jogar possa definir um dia de jogo e o sistema realizar o convite para dar quórum.
 
	[LRE007] Definir um controle de venda de refrigerantes.
```
---

## 📘 Parte 1 – Referências Clássicas e Acadêmicas

### 🔸 **Engenharia de Requisitos**
- **SOMMERVILLE, Ian** – *Engenharia de Software*, 9ª ed.
  - Cap. 4: Engenharia de Requisitos (p. 85–122)
  - Cap. 5: Modelos de Requisitos (p. 123–150)
  
- **MACHADO, Felipe Nery** – *Análise e Gestão de Requisitos de Software*
  - Cap. 2: Levantamento e análise de requisitos (p. 31–70)
  - Cap. 5: Qualidade e rastreabilidade dos requisitos (p. 121–135)

- **PFLEEGER, Shari** – *Engenharia de Software: Teoria e Prática*, 2ª ed.
  - Cap. 4: Comunicação com o cliente (p. 95–120)
  - Cap. 6: Rastreabilidade e mudanças (p. 147–165)

### 🔸 **Especificação e Modelagem**
- **BEZERRA, Eduardo** – *Princípios de Análise e Projeto de Sistemas com UML*
  - Cap. 3: Análise de requisitos (p. 45–78)
  - Cap. 4: Casos de uso e diagramas (p. 79–110)

- **DENNIS, Alan et al.** – *Análise e Projeto de Sistemas*, 5ª ed.
  - Cap. 3: Requisitos e metodologias (p. 70–102)
  - Cap. 4: Técnicas de levantamento (p. 103–130)

### 🔸 **Suporte e Estratégia**
- **SCHACH, Stephen R.** – *Engenharia de Software*, 7ª ed.
  - Cap. 5: Engenharia de requisitos (p. 98–132)

- **TONSIG, Sérgio Luiz** – *Engenharia de Software: Análise e Projeto de Sistemas*, 2ª ed.
  - Cap. 4: Levantamento e especificação (p. 87–105)

- **SBROCCO, José Henrique** – *Metodologias Ágeis: Engenharia de Software sob Medida*
  - Cap. 3: Priorização e foco nos requisitos essenciais (p. 51–72)

---

## 🌐 Parte 2 – Materiais Públicos, Acessíveis e Renomados

### 🔹 **Guia BABOK (Business Analysis Body of Knowledge)** – IIBA
- Capítulo 10: Requirements Life Cycle Management
- Disponível em: https://www.iiba.org/babok-guide/

### 🔹 **Guia PMBOK – Project Management Institute
