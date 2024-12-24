# POO - UnB
Estudo de programação orientada a objetos, utilizando Java e UML.

### 1 - Pesquise nas bibliografias sugeridas as definições sobre os seguinte termos:
- a) Classe
  - Uma classe é o estêncil a partir do qual são criados objetos, ela serve como um modelo ou planta baixa para criar objetos específicos que compartilham características semelhantes e comportamentos definidos.
- b) Objeto
  - O objeto é o que você cria a partir de uma classe.
- c) Elementos de classe
- d) Métodos construtores
- e) Métodos destrutores
- f) Estado
  - O espaço-estado de uma classe C é a totalidade de todos os estados
permitidos de qualquer objeto da classe C, o estado de um objeto é o conjunto ordenado
de objetos aos quais os objetos se referem em determinado tempo.
- g) Retenção de estado
  - Retenção de estado refere-se à capacidade de um objeto em orientação a objetos de manter e gerenciar seus dados ou atributos ao longo do tempo, um objeto se comporta igual a um hominóide, pois ele é ciente do seu passado. Ou seja, um objeto não "morre" após ser executado. Tecnicamente falando, um objeto retém estado.
- h) Associação entre objetos
- i) Pacotes
- j) Modificadores de acesso
- k) Ocultação de informação
   - As informações dentro da unidade não podem ser percebidas a partir do lado de fora da mesma, utiliza-se encapsulamento para restringir a visibilidade externa de certos detalhes de informações ou implementações, os quais são internos à estrutura de encapsulamento. Os atributos de uma classe devem ser declarados como privados ou protegidos, para restringir o acesso direto a eles por partes externas do código. Em vez de acessar ou modificar diretamente os atributos de um objeto, devem-se fornecer métodos públicos (getters e setters) para isso.

- l) Escopo de elementos
- m) Modificadores de escopo
- n) Herança
   - A herança permite que uma classe (chamada de classe derivada ou subclasse) herde atributos e métodos de outra classe (chamada de classe base, superclasse ou pai). Isso significa que a classe derivada pode aproveitar a estrutura e comportamentos já definidos na classe base, estendendo ou modificando seu comportamento conforme necessário.
- o) Generalização
   - Processo onde classes mais específicas (subclasses) são unificadas em uma classe mais genérica (superclasse). É o oposto de especialização, onde você cria novas classes a partir de uma mais genérica.
- p) Especialização
   - O oposto da generalização. Refere-se à criação de classes mais específicas (subclasses) a partir de uma classe genérica (superclasse).
- q) Polimorfismo
   - O conceito de "múltiplas formas". Em programação orientada a objetos, significa que uma mesma operação (como um método) pode se comportar de maneiras diferentes, dependendo do objeto que a chama.
- r) Sobrescrita de métodos
   - Refere-se ao ato de uma subclasse redefinir um método da superclasse, fornecendo uma implementação específica. A assinatura do método na subclasse deve ser a mesma da superclasse.
- s) Sobrecarga de métodos
   - É quando você tem vários métodos com o mesmo nome, mas com diferentes parâmetros (número ou tipo de parâmetros). Isso permite chamar o mesmo método com diferentes formas de entrada.
- t) Polimorfismo por coerção
   - Ocorre quando o tipo de um objeto é convertido automaticamente (por exemplo, de um tipo mais específico para um tipo mais genérico), permitindo que ele seja tratado como se fosse de outro tipo.
- u) Polimorfismo por inclusão
   - Também conhecido como polimorfismo de herança. Refere-se ao fato de que um objeto de uma subclasse pode ser tratado como se fosse um objeto da superclasse. Por exemplo, um objeto da classe Cachorro pode ser tratado como um objeto da classe Animal se Cachorro herdar de Animal.
- v) Polimorfismo paramétrico
   - É o polimorfismo implementado por meio de tipos genéricos. Ou seja, você define funções ou classes que podem trabalhar com diferentes tipos de dados sem definir explicitamente o tipo. Por exemplo, em Java, C# ou C++, isso é implementado com o uso de "generics".

## 2 - Apresente os modificadores de acesso informando qual o nível de visibilidade que cada um deles fornece.
### Public: 
- Se o modificador for público, então uma suposta característica c, será visível para qualquer objeto e c será herdada pelas subclasses de uma classe C. E em UML um modificador público é representado pelo carácter "+".
### Protected:
- Se o modificador for protegido, então c será visível só para os objetos da classe C e para os objetos das subclasses de C. E em UML é representado pelo carácter "#".
### Private:
- Se o modificador for privado, então c será visível apenas para os objetos da classe C e nesse caso c não será herdada pelas subclasses de C. É representado pelo carácter "-" em UML.

