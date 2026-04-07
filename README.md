# dio-notebook-llm
https://notebooklm.google.com/notebook/149a2915-3442-45fe-986b-09c3c10c37f8

### Curadoria de Fontes
- https://youtu.be/HcDJdKfm5nA
- https://youtu.be/p1bjHvX-DqM
- https://youtu.be/0dRPPmRYM3o
- https://youtu.be/zrWEJYIxpok
- https://testing-library.com/docs/react-testing-library/intro/
- https://www.objective.com.br/insights/teste-unitario/
- https://dev.to/griseduardo/testes-unitarios-em-react-com-jest-e-testing-library-56f3
- https://dayvsonlima.medium.com/entenda-de-uma-vez-por-todas-o-que-s%C3%A3o-testes-unit%C3%A1rios-para-que-servem-e-como-faz%C3%AA-los-2a6f645bab3

### Engenharia de Prompts e "Cicatrizes"

<details>
  <summary>Explique o padrão AAA para estruturar testes unitários.</summary>
  
    O padrão Triple A (Arrange, Act, Assert) é uma forma convencional de estruturar a escrita de testes unitários para torná-los mais claros e organizados.
    Ele divide o teste em três etapas principais:
    1. Arrange (Preparação/Arrumação): 
    Nesta primeira fase, você prepara o ambiente de teste e define o cenário. Isso inclui instanciar objetos, configurar variáveis necessárias, mocar dependências e renderizar componentes. O objetivo é deixar tudo pronto para que a unidade de código possa ser executada.
    2. Act (Ação): 
    É a etapa onde você efetivamente executa a ação ou o método que está sendo testado
    . No contexto de uma aplicação front-end, por exemplo, pode ser a simulação de um clique do usuário em um botão ou a chamada de uma função específica.
    3. Assert (Afirmação/Verificação): 
    Na fase final, você realiza as verificações ou asserções para garantir que o comportamento foi o esperado. 
    
    É aqui que se valida se o resultado obtido da ação coincide com o resultado esperado, como verificar se um elemento apareceu na tela ou se uma função foi chamada com os parâmetros corretos.
    Embora o padrão sugira três etapas, em cenários mais simples, como testar se um componente renderiza corretamente sem erros, o teste pode conter apenas as fases de Arrange (renderização) e Assert (verificar se o elemento está presente), sem a necessidade de uma ação intermediária (Act).
    A utilização deste padrão auxilia na manutenção do código, pois permite que qualquer desenvolvedor identifique rapidamente o que está sendo preparado, o que está sendo executado e o que está sendo validado em cada cenário de teste.
    
</details>

  #### Question
    
  #### Answer
    
