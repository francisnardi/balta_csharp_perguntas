1. O C# é uma linguagem compilada, tipada e gerenciada, o que isto significa?

    O C# é uma linguagem compilada, tipada e gerenciada. Isso significa que o código-fonte escrito em C# é traduzido para código de máquina executável antes da execução do programa. A tipagem significa que todas as variáveis devem ter um tipo definido e verificado em tempo de compilação. A gerência significa que o ambiente de execução (como o CLR do .NET) gerencia automaticamente a alocação e desalocação de memória, coleta de lixo e outras tarefas de gerenciamento, facilitando o desenvolvimento e aumentando a segurança.

2. O que diferencia uma linguagem compilada de uma interpretada?

    Uma linguagem compilada é traduzida para código de máquina executável antes da execução do programa. O código resultante da compilação é geralmente específico para a plataforma em que será executado. Por outro lado, uma linguagem interpretada é executada por meio de um interpretador em tempo de execução. O código-fonte é lido e traduzido para instruções executáveis linha por linha durante a execução. Isso torna as linguagens interpretadas geralmente mais portáteis, pois o interpretador pode ser executado em diferentes plataformas.

3. Explique como o C# funciona.

    O C# é uma linguagem de programação moderna desenvolvida pela Microsoft. Ela faz parte da plataforma .NET e é projetada para desenvolver uma variedade de aplicativos, desde aplicativos de desktop até aplicativos web e móveis. O C# é uma linguagem orientada a objetos, com suporte a recursos como herança, polimorfismo, encapsulamento e muito mais. Os programas em C# são compilados em uma linguagem intermediária chamada IL (Intermediate Language) que é executada no Common Language Runtime (CLR) do .NET.

4. O que é o CLR?

    O CLR (Common Language Runtime) é a parte central do ambiente de execução do .NET. É responsável por fornecer recursos avançados de execução, gerenciamento de memória, segurança, tratamento de exceções, coleta de lixo e suporte a várias linguagens de programação que podem ser compiladas para o CLR. O CLR garante a execução segura e confiável de aplicativos .NET.

5. O que é IL?

    IL (Intermediate Language) é uma linguagem de programação de nível baixo que é compilada a partir do código-fonte em C# (ou outras linguagens .NET). É uma representação independente de plataforma do código-fonte que é executada no CLR. O código IL é convertido em código de máquina específico para a plataforma em tempo de execução, o que permite que os programas .NET sejam executados em diferentes sistemas operacionais e arquiteturas de hardware.

6. O que é um Framework?

    Um framework é um conjunto de bibliotecas, ferramentas e padrões que fornecem uma estrutura para desenvolver aplicativos. Ele fornece um conjunto de funcionalidades comuns que podem ser reutilizadas em diferentes projetos, acelerando o desenvolvimento e fornecendo uma base sólida para construir aplicativos. No caso do .NET, o framework .NET é uma plataforma de desenvolvimento que inclui o CLR, bibliotecas de classes, ferramentas de desenvolvimento e muito mais.

7. O que é o .NET?

    O .NET é uma plataforma de desenvolvimento criada pela Microsoft que permite desenvolver e executar aplicativos em uma variedade de dispositivos e sistemas operacionais. Ele inclui o Common Language Runtime (CLR), bibliotecas de classes, linguagens de programação (como C# e VB.NET), ferramentas de desenvolvimento e um conjunto de tecnologias que facilitam a criação de aplicativos de alto desempenho, seguros e interoperáveis.

8. O que é o .NET Standard?

    O .NET Standard é uma especificação que define um conjunto de APIs (Application Programming Interfaces) comuns disponíveis em diferentes implementações do .NET, como .NET Framework, .NET Core e Xamarin. O objetivo do .NET Standard é fornecer uma base consistente de funcionalidades que podem ser usadas em diferentes plataformas .NET, permitindo que as bibliotecas sejam compartilhadas e reutilizadas entre diferentes projetos e implementações do .NET.

9. Explique o que é versão semântica.

    - A versão semântica é uma convenção de nomenclatura usada para indicar as versões de um software de maneira padronizada e significativa. Ela consiste em três números separados por pontos: MAJOR.MINOR.PATCH.

    - O número MAJOR é incrementado quando há mudanças incompatíveis na API.

    - O número MINOR é incrementado quando funcionalidades são adicionadas de forma retrocompatível.

    - O número PATCH é incrementado quando são feitas correções de bugs ou pequenas alterações que não afetam a compatibilidade.

10. O que significa LTS na versão do software?

    LTS significa Long-Term Support (Suporte de Longo Prazo). É usado para indicar uma versão do software que receberá suporte e atualizações de segurança por um período estendido, geralmente vários anos. Essas versões são recomendadas para uso em ambientes de produção, onde a estabilidade e a confiabilidade são prioritárias em relação às novas funcionalidades.

11. O que é um Runtime?

    Um Runtime (Ambiente de Execução) é uma camada de software responsável por executar e gerenciar a execução de aplicativos. Ele fornece um conjunto de recursos essenciais, como alocação de memória, gerenciamento de recursos, execução de código intermediário, coleta de lixo e tratamento de exceções. No contexto do .NET, o Common Language Runtime (CLR) é o runtime principal que executa aplicativos .NET.

12. O que é um SDK?

    SDK (Software Development Kit) é um conjunto de ferramentas, bibliotecas e documentação fornecidas para facilitar o desenvolvimento de software para uma plataforma específica. Em relação ao .NET, o SDK do .NET fornece as ferramentas necessárias para desenvolver, depurar e publicar aplicativos .NET. Ele inclui compiladores, bibliotecas de classes, utilitários de linha de comando e outros recursos relacionados ao desenvolvimento.

13. O que é um CLI?

    CLI (Command-Line Interface) é uma interface de linha de comando que permite interagir com um sistema operacional ou um software por meio de comandos digitados em um terminal ou prompt de comando. No contexto do .NET, a CLI do .NET (também conhecida como dotnet CLI) é uma interface de linha de comando fornecida pelo SDK do .NET. Ela permite executar comandos relacionados ao desenvolvimento .NET, como criar projetos, compilar código, executar testes e publicar aplicativos. A CLI do .NET é multiplataforma e suporta várias tarefas de desenvolvimento.

14. Cite 3 tipos de projetos que temos no .NET

    Alguns tipos de projetos que podemos encontrar no .NET são:

    - Console App: Um projeto de aplicativo de console, que permite a criação de aplicativos executados em um prompt de comando.
    
    - Web App: Um projeto de aplicativo da web, que permite a criação de aplicativos web utilizando frameworks como ASP.NET.
    
    - Class Library: Um projeto de biblioteca de classes, que é utilizado para criar bibliotecas reutilizáveis de código.

15. O que é uma Solution?

    Uma Solution (solução) no contexto do desenvolvimento .NET é um arquivo que agrupa e gerencia um ou mais projetos relacionados. Ela fornece uma estrutura organizacional para o desenvolvimento e implantação de aplicativos. A Solution inclui referências aos projetos, configurações de compilação e implantação, e facilita a interação entre os projetos dentro do ambiente de desenvolvimento integrado (IDE).

16. Qual comando para executar uma aplicação .NET?

	O comando para executar uma aplicação .NET depende do tipo de aplicação e do ambiente em que está sendo executada. Para um Console App, por exemplo, você pode executar o comando "dotnet run" no diretório do projeto para iniciar a aplicação.

17. Qual comando para compilar uma aplicação .NET?

	O comando para compilar uma aplicação .NET também depende do tipo de aplicação. Para um projeto simples, você pode executar o comando "dotnet build" no diretório do projeto para compilar o código-fonte e gerar os arquivos binários executáveis.

18. Qual comando para publicar uma aplicação .NET?

	O comando para publicar uma aplicação .NET também varia dependendo do tipo de aplicação e do destino da publicação. Para um projeto de aplicativo web, você pode usar o comando "dotnet publish" no diretório do projeto para publicar o aplicativo em um formato adequado para implantação em um servidor web.

19. Qual nome do método principal de um Console App?

	O nome do método principal de um Console App em C# é "Main". É o ponto de entrada do programa, onde a execução começa. O método Main pode receber argumentos de linha de comando como parâmetros e é onde você escreve o código que deseja que o aplicativo execute.

20. O que significa Debug?

	Debug é o processo de execução e análise de um programa passo a passo para identificar erros, encontrar falhas de lógica e entender o comportamento do código durante a execução. Em desenvolvimento de software, a depuração é uma técnica essencial para corrigir bugs e problemas de funcionamento em um programa. Ela envolve a inspeção de variáveis, a execução controlada do código e o uso de ferramentas de depuração para identificar e resolver problemas.

21. Como executamos uma aplicação .NET em modo Debug?

	Para executar uma aplicação .NET em modo Debug, você pode seguir os seguintes passos:

    - Abra o projeto no Visual Studio.

    - Certifique-se de que o projeto está configurado para ser compilado em modo de depuração (Debug mode). Você pode verificar isso no menu "Build" -> "Configuration Manager" e certificar-se de que a configuração ativa é "Debug".

    - Defina os pontos de interrupção (breakpoints) no código onde você deseja pausar a execução para fins de depuração.

    - Pressione F5 ou escolha "Debug" -> "Start Debugging" no menu para iniciar a depuração.

    - O Visual Studio será iniciado em modo de depuração e a execução do programa será pausada nos pontos de interrupção definidos. Você pode usar as ferramentas de depuração do Visual Studio para examinar variáveis, acompanhar o fluxo do programa e identificar erros.

22. Qual a finalidade da pasta Properties?

	A pasta "Properties" em um projeto .NET tem a finalidade de armazenar arquivos relacionados às configurações e propriedades do projeto. Esses arquivos podem incluir:

    - AssemblyInfo.cs: Um arquivo que contém informações sobre a versão, título, descrição, informações de copyright e outras propriedades do assembly.

    - Settings.settings: Um arquivo que pode ser usado para definir configurações personalizadas para o projeto, como configurações de aplicativo.

    - Resources.resx: Um arquivo que pode ser usado para armazenar recursos estáticos, como strings localizadas, imagens ou outros arquivos de recursos.

    Esses arquivos contidos na pasta "Properties" são usados para configurar e personalizar o comportamento do projeto durante a compilação e execução.

23. Qual a finalidade das pastas Bin e Obj?

	As pastas "Bin" e "Obj" são pastas geradas durante o processo de compilação de um projeto .NET.

    - A pasta "Bin" (Binary) contém os arquivos binários resultantes da compilação, como os arquivos executáveis (.exe) e bibliotecas de classes (.dll) do projeto. Esses arquivos são os artefatos finais que são usados para executar ou distribuir o projeto.

    - A pasta "Obj" (Object) contém arquivos temporários gerados durante o processo de compilação. Esses arquivos são usados para armazenar os resultados intermediários da compilação, como arquivos de objeto (.obj) e outros arquivos auxiliares necessários para criar o executável ou biblioteca final.

24. Quais partes compoe um programa em C#?

	Um programa em C# é composto por várias partes, incluindo:

    - Namespace: Um programa pode estar contido em um ou vários namespaces, que são espaços para agrupar classes relacionadas.

    - Classes: As classes são as unidades básicas de organização em C#. Elas contêm membros, como métodos, propriedades, campos e eventos, que definem o comportamento e a estrutura dos objetos.

    - Métodos: Os métodos são blocos de código que realizam ações específicas. Eles podem receber argumentos, executar instruções e retornar um valor, se necessário.

    - Propriedades: As propriedades permitem acessar e manipular valores de uma classe. Elas podem ter um getter (obter valor) e um setter (definir valor), ou apenas um deles.

    - Campos: Os campos são variáveis declaradas dentro de uma classe que armazenam dados específicos para cada instância da classe.

    - Eventos: Os eventos permitem que uma classe notifique outras classes quando algo interessante acontece.

    - Estruturas de controle: C# oferece estruturas de controle, como loops (for, while), condicionais (if, switch) e estruturas de controle de fluxo (break, continue), para controlar o fluxo de execução do programa.

25. O que são Namespaces?

	

26. Qual a finalidade do Using?

	

27. Qual a diferença entre uma variável e uma constante?

	

28. Cite 3 nomes reservados que temos no C#

	

29. Quais formas temos de comentar código em C#?

	

30. O que são tipos primitivos?

	

31. Qual tipo base no .NET?

	

32. Dado um var de um número real, qual tipo seria o var?

	

33. Dado um var de um número inteiro, qual tipo seria o var?

	

34. Qual a diferença entre char e string?

	

35. Qual valor padrão do tipo char?

	

36. Qual a diferença entre var e object?

	

37. O que são tipos nulos?

	

38. O que são alias? Cite 3 exemplos

	

39. O que são conversões implícitas?

	

40. O que são conversões explícitas?

	

41. Qual a diferença entre parse e Convert?

	

42. O que são operadores aritméticos e quais temos no C#?

	

43. O que são operadores de atribuição e quais temos no C#?

	

44. O que são operadores de comparação e quais temos no C#?

	

45. O que são operadores lógicos e quais temos no C#?

	

46. Cite duas estruturas condicionais que temos no C#

	

47. Cite duas estruturas de repetição que temos no C#

	

48. Qual a diferença entre while e do/while?

	

49. Como definimos que um método não retorna valor algum?

	

50. Podemos ter métodos sem parâmetros no C#?

	

51. Como tornamos um parâmetro opcional no C#?

	

52. O que são heap e stack?

	

53. O que são tipos de valor e tipos de referência?

	

54. Onde são armazenados os tipos de valor?

	

55. Onde são armazenados os tipos de referência?

	

56. O que são Structs?

	

57. O que são enumeradores?

	

58. O que é um GUID?

	

59. O que é interpolação de String?

	

60. Qual a finalidade do método CompareTo?

	

61. Qual a finalidade do método Contains?

	

62. Qual a finalidade do método StartsWith e EndsWith?

	

63. Qual a finalidade do método Equals?

	

64. Qual a finalidade do método IndexOf e LastIndexOf?

	

65. Qual a finalidade do método ToLower e ToUpper?

	

66. Qual a finalidade do método Insert?

	

67. Qual a finalidade do método Length?

	

68. Qual a finalidade do método Remove?

	

69. Qual a finalidade do método Replace?

	

70. Qual a finalidade do método Split?

	

71. Qual a finalidade do método Substring?

	

72. Qual a finalidade do método Trim?

	

73. O que é StringBuilder e quando devemos utilizar?

	

74. O que é Regex e quando devemos utilizar?

	

75. O que é o DateTime?

	

76. Como obtemos a data de hoje no C#?

	

77. Como convertemos uma data para String?

	

78. Como comparamos duas datas em C#?

	

79. Como podemos obter o ano, mês ou dia no C#?

	

80. Como podemos obter o último dia do mês no C#?

	

81. Podemos criar datas nulas?

	

82. O que são nullable types?

	

83. O que é Timezone?

	

84. Como obtermos a data sem um Timezone no C#?

	

85. O que é DateTime Offset?

	

86. O que é um TimeSpan?

	

87. Qual a finalidade do Math.Round, Math.Celling e Math.Floor?

	

88. Qual a diferença entre IEnumerable, IList e ICollection?

	

89. Qual a diferença entre List e IList?

	

90. Qual a finalidade do método Add e AddRange em uma lista?

	

91. Qual a finalidade do método Clear em uma lista?

	

92. Qual a finalidade do método Contains em uma lista?

	

93. Qual a finalidade do método CopyTo em uma lista?

	

94. Qual a finalidade do método Exists em uma lista?

	

95. Qual a finalidade do método Find e FindAll em uma lista?

	

96. Qual a finalidade do método IndexOf e LastIndexOf em uma lista?

	

97. Qual a finalidade do método FindIndex, FindLast e FindLastIndex em uma lista?

	

98. Qual a finalidade do método Insert e InsertRange em uma lista?

	

99. Qual a finalidade do método Remove, RemoveAll, RemoveAt e RemoveRange em uma lista?

	

100. Qual a finalidade do método Reverse em uma lista?

	

101. Qual a finalidade do método Sort em uma lista?

	

102. Qual a finalidade do método ToArray em uma lista?

	

103. Qual a finalidade do método TrueForAll em uma lista?

	

104. Qual a finalidade do método ConvertAll em uma lista?

	

105. Qual a finalidade do método ForEach em uma lista?

	

106. Qual a finalidade do método Where em uma lista?

	

107. Qual a finalidade do método First em uma lista?

	

108. Qual a finalidade do método OrderBy em uma lista?

	

109. Qual a finalidade do método Sort em uma lista?

	

110. Qual a finalidade do método Select em uma lista?

	

111. Qual a finalidade do método Convertendo Listas em uma lista?

	

112. O que são Classes e Objetos?

	

113. O que é uma instância?

	

114. O que são Propriedades?

	

115. O que são Métodos construtores?

	

116. O que é o Garbage Collector?

	

117. O que é Object Dispose?

	

118. Defina os modificadores public, private e protected

	

119. O que são objetos estáticos?

	

120. O que é Herança?

	

121. O que é Upcast e Downcast?

	

122. O que são Interfaces?

	

123. O que são Classes abstratas?

	

124. Qual a finalidade das Classes seladas?

	

125. O que é Sobrecarga de métodos?

	

126. O que é Sobrescrita de método?

	

127. Como podemos Comparar dois objetos no C#?

	

128. Qual a finalidade do Dispose?

	

129. O que é Encapsulamento?

	

130. O que é Polimorfismo?

	

131. O que são Tipos complexos?

	

132. O que são Delegates?

	

133. O que são events?

	

134. Qual a diferença entre Events e Delegates?

	

135. O que são os generics?

	

136. Como restringimos um tipo genérico?

	

137. Como tratamos erros no C#?

	

138. Qual a finalidade do finally?

	

139. Para que serve o Try/Parse?

	

140. O que são Tasks?

	

141. Para que serve async/await?

	

142. Qual a diferença entre Task.FromResult e o uso de await?

	

143. Para que usamos a interface IEquatable?

	

144. Para que usamos a interface IComparable?

	

145. Quando utilizamos a interface IDisposable?

	

146. O que são Extension methods?