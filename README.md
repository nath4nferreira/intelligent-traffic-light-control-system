# Intelligent Traffic Light control system - CLP

-> Sobre o Projeto Este projeto apresenta o desenvolvimento de um sistema automatizado de semáforo inteligente com botoeira para travessia de pedestres, utilizando Controlador Lógico Programável (CLP), linguagem Ladder e simulação no MacroPLC.

O objetivo é garantir a segurança dos pedestres sem comprometer a fluidez do tráfego, permitindo que solicitações de travessia sejam registradas e atendidas de forma segura durante a fase apropriada do ciclo semafórico.

🎯 Objetivos Projetar e implementar um sistema de controle semafórico em CLP; Desenvolver a lógica de automação em linguagem Ladder; Implementar uma botoeira de solicitação para pedestres; Garantir intertravamento seguro entre os sinais; Simular e validar o funcionamento do sistema no MacroPLC.

⚙️ Tecnologias Utilizadas CLP (Controlador Lógico Programável) Linguagem Ladder (IEC 61131-3) MacroPLC Automação Industrial

🏗️ Funcionalidades Semáforo veicular com três estados:

🟢 Verde

🟡 Amarelo

🔴 Vermelho

Sinalização dedicada para pedestres;

Registro de solicitação por botoeira;

Memória selada para não perder solicitações;

Temporizadores em cascata;

Operação automática e determinística.

📊 Resultados Os testes de simulação validaram:

Funcionamento correto do ciclo semafórico; Atendimento das solicitações dos pedestres; Ausência de conflitos entre sinais; Operação estável em todos os cenários simulados.
