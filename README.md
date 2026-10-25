# Pica-Ponto-Driver-._.
Pica ponto para motoristas TVDE

# 🚖 Pica Ponto Driver

O **Pica Ponto Driver** é uma aplicação Android desenvolvida nativamente em **Jetpack Compose (Material 3)**, concebida especificamente para motoristas TVDE (como operadores na Uber ou Bolt). A aplicação ajuda a gerir o tempo de trabalho em tempo real, cumprir os limites legais de condução, controlar pausas, monitorizar ganhos e exportar relatórios detalhados.

---

## ✨ Principais Funcionalidades

### ⏱️ Gestão de Turnos e Atividades
* **Controlo em Tempo Real:** Iniciar, pausar, retomar (Condução, Pausa, Refeição) e terminar turnos.
* **Registo de Quilometragem:** Registo opcional ou obrigatório de quilómetros iniciais e finais por turno.
* **Cálculo de Horas Efetivas:** Contagem precisa de horas de condução e tempos de descanso.

### 🫧 Widget e Botão Flutuante (Overlay)
* **Controlo Sobre Outras Apps:** Permite gerir o turno e alternar entre condução/pausa por cima da Uber ou Bolt sem precisar de abrir a app principal.
* **Cronómetro Dinâmico:** Mostra o tempo de condução ou o tempo em pausa/almoço a atualizar segundo a segundo em tempo real.

### ⚠️ Alertas de Conformidade TVDE
* **Monitorização de Limites:** Avisos automáticos baseados nas normas legais (ex: limite diário de 10h de condução e máximo de 6h de trabalho contínuo sem pausa).
* **Overlay de Alertas:** Notificações visuais de urgência diretamente no ecrã.

### 📊 Análise de Ganhos e Desempenho
* **Registo Diário:** Inserção de ganhos da Uber e Bolt, quilómetros percorridos e horas trabalhadas. (atenção que alguns valores apenas o operador tem acesso, ignorar esses campos caso nao tenha acesso detalhado aos mesmos)
* **Estatísticas Semanais e Mensais:** Visualização de ganhos por hora e por quilómetro (`€/h` e `€/km`).
* **Backup e Restauro:** Exportação e importação de dados financeiros em formato JSON, além de exportação para CSV.
* **Semana de Trabalho:** Calendário e métricas configurados de **Segunda-feira a Domingo**.

### 📄 Relatórios Oficiais em PDF
* **Exportação Profissional:** Geração de relatórios em PDF com dados do motorista e operador TVDE.
* **Organização Cronológica:** Resumo diário e turnos detalhados ordenados rigorosamente por **Ano, Mês e Dia**.
* **Rodapé Profissional:** Identificação da app e carimbo com a data e hora exata da exportação (`Exportado a dd/MM/yyyy às HH:mm`).
* **Campo oculto de ediçao** No Separador da lei TVDE existe um campo oculto de ediçao no final da página que abre apos 5 cliques, apos abertura coloquem um codigo vosso para que nao esueçam, devera ser sempre usado para reentrar novamente nesse espaço, por questões legais nao pode ficar ficar visivel para ediçao livre.

---

## ⚖️ Termo de Responsabilidade e Salvaguarda Legal (Disclaimer)

**Por favor, leia atentamente as seguintes condições antes de utilizar a aplicação:**

* **Carácter Informativo e Auxiliar:** O **Pica Ponto Driver** é uma ferramenta de desenvolvimento independente e de uso pessoal, concebida para auxiliar na organização do tempo de trabalho. **Esta aplicação não possui homologação oficial pelas autoridades competentes nem substitui os mecanismos formais de controlo de tempo exigidos por lei.**
* **Aproximação Legal:** À data, não existem aplicações móveis comerciais oficialmente validadas para este efeito. O desenvolvimento desta app teve como critério a aproximação máxima e rigorosa aos requisitos descritos na legislação em vigor para motoristas e operadores TVDE. No entanto, devido à complexidade técnica e jurídica, o cumprimento total de todas as obrigações legais através desta ferramenta não pode ser garantido.
* **Uso por Conta e Risco:** A utilização desta aplicação em contexto pessoal ou profissional é da **exclusiva responsabilidade do utilizador**. 
* **Exclusão de Responsabilidade:** O criador/desenvolvedor desta aplicação **não se responsabiliza** por quaisquer coimas, sanções, litígios laborais, perda de dados, divergências de quilometragem/horários com operadores (Uber, Bolt, etc.), ou qualquer outro dano direto ou indireto decorrente do uso ou da interpretação dos dados gerados por esta app.

