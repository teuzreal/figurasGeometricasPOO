# **Figuras Geométricas - Programação Orientada a Objetos (POO)**

Este repositório foi desenvolvido com o objetivo de demonstrar, de forma clara e prática, os principais conceitos da **Programação Orientada a Objetos (POO)** aplicados ao cálculo de áreas e volumes de **figuras geométricas planas e espaciais**. O projeto está organizado em diretórios específicos para cada conceito de POO, utilizando uma abordagem modular com pacotes separados para facilitar o entendimento e a reutilização de código.

---

###  **Conceitos Abordados**
- **Abstração**
- **Encapsulamento**
- **Herança**

---

###  **Estrutura do Projeto**

O projeto está dividido em três diretórios principais, cada um ilustrando um conceito fundamental da Programação Orientada a Objetos:

---

###  `figurasGeometricas-Abstracao`

Este diretório demonstra o conceito de **Abstração**, com foco em esconder os detalhes internos do funcionamento das figuras e expor apenas o necessário.

#### 📁 `br.edu.principal`
- Contém o método `main`, que realiza testes com as classes.

#### 📁 `br.edu.figurasgeometricasplanas`
- Contém classes abstratas e concretas que representam figuras geométricas planas.

#### UML - Diagrama de Classes (Abstração)

*****img

---

###  `figurasGeometricas-Encapsulamento`

Este diretório explora o conceito de **Encapsulamento**, protegendo atributos e controlando o acesso por meio de métodos `get` e `set`.

#### 📁 `br.edu.principal`
- Classe principal com chamadas aos métodos encapsulados.

#### 📁 `br.edu.figurasgeometricasplanas`
- Figuras planas como: Triângulo, Retângulo, Losango, etc.

#### 📁 `br.edu.figurasgeometricasespacias`
- Figuras espaciais como: Cubo, Esfera, Cilindro, Cone, etc.

#### UML - Diagrama de Classes (Encapsulamento)

*****img

---

###  `figurasGeometricas-Heranca`

Neste diretório é evidenciado o uso de **Herança**, onde classes derivadas compartilham atributos e métodos de superclasses, promovendo **reutilização de código** e redução de redundância.

#### 📁 `br.edu.principal`
- Contém o ponto de entrada do programa.

#### 📁 `br.edu.figurasgeometricasplanas`
- Subclasses que herdam de uma classe base `FiguraPlana`.

#### 📁 `br.edu.figurasgeometricasespacias`
- Subclasses que herdam de uma classe base `FiguraEspacial`.

#### UML - Diagrama de Classes (Herança)

*****img

---

##  **Figuras Geométricas Implementadas**

### Figuras Planas
- Triângulo
- Retângulo
- Quadrado
- Círculo
- Trapézio
- Paralelogramo
- Losango
- Pentágono
- Hexágono

###  Figuras Espaciais
- Cubo
- Prisma
- Esfera
- Pirâmide
- Cone
- Cilindro
- Paralelepípedo
- Tetaedro

---

##  Métodos Implementados

Cada classe segue a estrutura:
- Atributos privados
- Construtor para inicialização
- Métodos:
  - `calcArea()`
  - `calcVolume()`
