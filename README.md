Worker Income Calculator
Este projeto em Java é um calculador de renda de um trabalhador com base em seu salário base e contratos por hora, organizados por mês e ano.

📌 Descrição
O sistema:

Recebe dados de um trabalhador (nome, nível e salário base).

Recebe os contratos por hora trabalhados (data, valor por hora e horas).

Calcula a renda total em um mês específico com base nos contratos cadastrados + salário base.

Utiliza conceitos de:

Orientação a objetos

Enumerações (WorkerLevel)

Tratamento de datas com SimpleDateFormat

Listas de contratos associados a cada trabalhador

Ideal para treinar POO em Java de forma prática.

🛠️ Tecnologias Utilizadas
Java (JDK 17 ou superior recomendado)

IDE de sua preferência (Eclipse, IntelliJ, VS Code)

Console para entrada de dados

🚀 Como executar
1️⃣ Clone o repositório:
git clone https://github.com/seu-usuario/worker-income-calculator.git

2️⃣ Abra o projeto em sua IDE.

3️⃣ Execute o arquivo Program.java.

💻 Exemplo de uso
Enter department's name: Design
Enter worker data:
Name: João Silva
Level: MID_LEVEL
Base salary: 1200.00
How many contracts to this worker? 2
Enter contract #1 data:
Date (DD/MM/YYYY): 20/06/2025
Value per hour: 50.00
Duration (hours): 20
Enter contract #2 data:
Date (DD/MM/YYYY): 13/06/2025
Value per hour: 30.00
Duration (hours): 18

Enter month and year to calculate income (MM/YYYY): 06/2025
Name: João Silva
Department: Design
Income for 06/2025: 2100.00

🧩 Estrutura do Projeto
entities/Department.java: classe do departamento.

entities/Worker.java: classe do trabalhador, com métodos para adicionar contratos e calcular renda.

entities/HourContract.java: classe do contrato de hora.

entities/enums/WorkerLevel.java: enum com os níveis (JUNIOR, MID_LEVEL, SENIOR).

application/Program.java: ponto de entrada do projeto.

🏗️ Conceitos Praticados
✅ Programação orientada a objetos
✅ Enums em Java
✅ Composição de classes
✅ Manipulação de datas
✅ Entrada de dados pelo console

📄 Licença
Este projeto é livre para fins de estudo e prática.
