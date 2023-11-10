# Sistema de Hospedagem em C# :hotel:

## Descrição do Projeto

Este é um projeto desenvolvido em C# que implementa um sistema de hospedagem para realizar reservas em um hotel fictício. O sistema conta com classes robustas, como `Pessoa`, `Suite`, e `Reserva`, estabelecendo um relacionamento entre hóspedes, suítes e reservas.

### Funcionalidades Principais

1. **Cadastro de Hóspedes:** O sistema permite o cadastro de hóspedes, representados pela classe `Pessoa`, incluindo informações como nome e sobrenome.

2. **Cadastro de Suítes:** Suítes são cadastradas com informações sobre o tipo de suíte, capacidade de hóspedes e valor da diária.

3. **Realização de Reservas:** A classe `Reserva` é responsável por realizar reservas, garantindo que a capacidade da suíte seja suficiente para o número de hóspedes. Além disso, a reserva calcula o valor total considerando o número de dias reservados, aplicando um desconto de 10% para reservas iguais ou superiores a 10 dias.

4. **Informações Detalhadas:** O sistema fornece informações detalhadas, como a quantidade de hóspedes, valor total da reserva e exibe mensagens de erro caso a capacidade da suíte seja insuficiente.

### Como Utilizar

Para experimentar o sistema, basta seguir os seguintes passos:

1. **Criar Hóspedes:** Crie instâncias da classe `Pessoa` para representar os hóspedes.

2. **Definir Suítes:** Utilize a classe `Suite` para cadastrar diferentes tipos de suítes, informando a capacidade e o valor da diária.

3. **Realizar Reservas:** A classe `Reserva` permite criar reservas associando hóspedes e suítes, indicando a quantidade de dias desejados.

4. **Obter Informações:** Utilize os métodos da classe `Reserva` para obter informações detalhadas, como a quantidade de hóspedes e o valor total da reserva.

### Considerações Finais

Este projeto serve como uma excelente base para a compreensão e prática de conceitos fundamentais em programação orientada a objetos (POO) com C#. Além disso, destaca-se pela implementação de regras de negócio importantes para um sistema de hospedagem.

Sinta-se à vontade para explorar, modificar e expandir este projeto de acordo com suas necessidades e aprendizados. Espero que seja útil em seu desenvolvimento profissional!
