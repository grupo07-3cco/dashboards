# NeoMonitor

Protótipos de dashboards para acompanhamento de uma unidade de terapia
intensiva neonatal (UTIN). Os arquivos são páginas HTML independentes e podem
ser abertos diretamente no navegador.

> **Atenção:** os dashboards utilizam dados simulados. Eles são ferramentas de
> apoio ao acompanhamento e não substituem equipamentos médicos regulamentados
> nem a avaliação de profissionais de saúde.

## Dashboards disponíveis

### Neonatologista

Painel destinado ao acompanhamento clínico individual de recém-nascidos.

- [Painel do Neonatologista (Dr. Rafael)](<Neonatologista_Dr.Rafael/NeoMonitor · Painel do Neonatologista (Dr. Rafael).html>)
- [Neonatologista (Dr. Rafael) — modo claro](<Neonatologista_Dr.Rafael/NeoMonitor · Neonatologista (Dr. Rafael) · Modo claro.html>)

Recursos principais:

- seleção do paciente e do período de análise (6, 12 ou 24 horas);
- histórico e tendências dos sinais monitorados, com faixas-alvo e marcadores
  de alertas;
- análise multivariável com escolha dos indicadores exibidos nos dois eixos;
- linha do tempo de alertas e intervenções;
- resumo da evolução do turno;
- impressão do resumo.

### Enfermagem

Painel destinado à monitorização operacional em tempo real da unidade.

- [Painel da Enfermagem (Mariana)](<Enfermeira_Mariana/NeoMonitor · Painel da Enfermagem (Mariana).html>)
- [Enfermagem (Mariana) — modo claro](<Enfermeira_Mariana/NeoMonitor · Enfermagem (Mariana) · Modo claro.html>)

Recursos principais:

- visão dos leitos e dos recém-nascidos monitorados;
- indicadores de frequência cardíaca, saturação de oxigênio, temperatura da
  incubadora e umidade;
- classificação visual dos estados **estável**, **atenção** e **crítico**;
- fila de priorização por gravidade e atraso da avaliação;
- mapa de camas, incluindo leitos livres e áreas de isolamento;
- simulação de alerta e controle do som dos alertas;
- atualização periódica das informações.

### Gestão hospitalar

Painel destinado à visão gerencial da UTIN e ao acompanhamento da operação.

- [Painel da Gestão (Alice)](<Gestora-Hospilatar_Alice/NeoMonitor · Painel da Gestão (Alice).html>)
- [Gestão (Alice) — modo claro](<Gestora-Hospilatar_Alice/NeoMonitor · Gestão (Alice) · Modo claro.html>)

Recursos principais:

- indicadores gerenciais da UTIN;
- seleção do período de análise (últimos 7 ou 30 dias);
- mapa de calor de alertas por dia da semana e horário;
- tempo médio de resposta por dia, com meta de até 5 minutos;
- identificação dos dias que excedem a meta;
- acompanhamento da saúde dos ativos IoT;
- exportação do relatório.

## Como abrir

1. Clone ou baixe este repositório.
2. Abra um dos arquivos `.html` listados acima diretamente no navegador.
3. Use os controles do próprio dashboard para trocar o período, selecionar
   pacientes ou simular alertas.

Os dashboards não possuem etapa de build nem servidor obrigatório. A fonte
`Figtree` é carregada do Google Fonts quando há conexão com a internet; sem
conexão, o navegador utiliza fontes alternativas do sistema.

## Aparência

Cada perfil possui uma versão padrão e uma versão explicitamente identificada
como **modo claro**. Os dashboards também foram preparados para responder à
preferência de tema do sistema quando essa preferência estiver disponível.

## Privacidade e uso

Os arquivos são protótipos locais com dados simulados. Não insira dados reais
de pacientes. O rodapé de cada dashboard reforça que o uso deve respeitar a
LGPD e que a ferramenta não substitui sistemas ou dispositivos médicos
regulamentados.
