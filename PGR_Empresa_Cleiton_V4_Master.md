# PROGRAMA DE GERENCIAMENTO DE RISCOS (PGR) - VERSÃO 4 (MASTER)
**Documento Base:** Gerenciamento de Riscos Ocupacionais (GRO)
**Status:** Versão Consolidada e Auditável

---

## CONTROLE DE VERSÕES E REVISÕES

| Versão | Data | Descrição da Alteração | Responsável |
| :--- | :--- | :--- | :--- |
| 1.0 | 16/01/2026 | Emissão Inicial - Foco em Riscos Críticos (NR-10/NR-35). | Eng. Segurança |
| 2.0 | 20/01/2026 | Estruturação do Inventário e Plano de Ação Executivo. | Eng. Segurança |
| 3.0 | 05/02/2026 | Inclusão de Planos de Emergência e Auditoria. | Eng. Segurança |
| **4.0** | **Data Atual** | **Integração Sistêmica, Checklists, Fluxogramas e Indicadores.** | **Eng. Segurança** |

---

## 1. INTRODUÇÃO E GOVERNANÇA

### 1.1. Objetivos
Este Programa tem como objetivo estabelecer as diretrizes para o **Gerenciamento de Riscos Ocupacionais (GRO)** da **Empresa Cleiton**, visando a prevenção de acidentes e doenças relacionadas ao trabalho, em estrito cumprimento à **NR-01** e normas correlatas.

### 1.2. Abrangência
O PGR abrange todas as atividades operacionais da empresa, com foco específico nas atividades de **Rede Externa (Telecomunicações)**, envolvendo trabalho em altura e proximidade com redes elétricas.

### 1.3. Referências Normativas
O programa foi estruturado observando os requisitos das seguintes normas:
*   **NR-01:** Disposições Gerais e Gerenciamento de Riscos Ocupacionais.
*   **NR-06:** Equipamento de Proteção Individual (EPI).
*   **NR-10:** Segurança em Instalações e Serviços em Eletricidade.
*   **NR-35:** Trabalho em Altura.
*   **NR-17:** Ergonomia.

---

## 2. METODOLOGIA DE AVALIAÇÃO DE RISCOS

A metodologia adotada segue o algoritmo quantitativo **"Passo a Passo"**, garantindo rastreabilidade e objetividade na classificação dos riscos.

### 2.1. Fluxo de Identificação e Análise
1.  **Levantamento:** Análise de documentos (APR, Livro de Ocorrências) e inspeção de campo.
2.  **Associação Legal:** Correlação do perigo com a infração legal (Ementa) correspondente.
3.  **Ponderação:** Atribuição de PESO baseada na gravidade da infração.

### 2.2. Matriz de Risco (Probabilidade x Severidade)

**Cálculo da Probabilidade (P):**
$$P = (\sum \text{Pesos das Infrações}) \times \text{Fator de Correção}$$
*   *Fator de Correção:* 1.25 (Aplicado devido ao histórico de quase-acidentes nos últimos 12 meses).

**Níveis de Risco:**
*   **1 - 5:** Trivial (Aceitável)
*   **6 - 10:** Moderado (Requer Atenção)
*   **11 - 15:** Alto (Medidas a Curto Prazo)
*   **> 15:** **Crítico (Paralisação/Imediato)**

---

## 3. CARACTERIZAÇÃO DO ESTABELECIMENTO E PROCESSOS

### 3.1. Dados da Empresa
*   **Razão Social:** Empresa Cleiton Telecomunicações Ltda.
*   **Setor:** Telecomunicações (CNAE Principal: Instalação e Manutenção).
*   **Local de Trabalho:** Vias públicas urbanas (Posteamento compartilhado).

### 3.2. Fluxograma do Processo de Trabalho (Instalação de Fibra)

```mermaid
graph TD
    A[Chegada ao Local] --> B{Análise de Risco (APR)};
    B -- Risco Controlado --> C[Sinalização da Área];
    B -- Risco Grave --> Z[Abortar/Solicitar Apoio];
    C --> D[Posicionamento da Escada];
    D --> E[Ancoragem da Escada];
    E --> F[Subida do Técnico];
    F --> G[Verificação de Tensão (Detector)];
    G --> H[Execução da Instalação];
    H --> I[Descida e Desmobilização];
```

---

## 4. INVENTÁRIO DE RISCOS OCUPACIONAIS (IRO)

### 4.1. Grupo de Risco: ACIDENTES (Mecânicos e Elétricos)

#### **Risco 01: Choque Elétrico e Arco Voltaico**
*   **Fonte Geradora:** Rede de Distribuição (BT/MT) da Concessionária.
*   **Cenário:** Trabalho em **Zona Controlada (< 60cm)** sem proteção adequada.
*   **Evidência:** Ocorrência #12 (Formigamento/Fuga de corrente).
*   **Análise de Conformidade (Ementas):**
    *   *Ementa 210189-0 (NR-10):* Falta de treinamento (Peso 3).
    *   *Ementa 210171-8 (NR-10):* Trabalho em Zona Controlada s/ procedimento (Peso 3).
    *   *Ementa 210122-0 (NR-10):* Falta de medidas preventivas/EPI (Peso 4).
*   **Avaliação Quantitativa:**
    *   Soma Pesos: 10
    *   Fator: 1.25
    *   Score Final: **12.5**
*   **Classificação:** **CRÍTICO (Nível 20)** - *Severidade Catastrófica*.

#### **Risco 02: Queda de Altura (> 2,0m)**
*   **Fonte Geradora:** Escada extensiva mal ancorada / Piso irregular.
*   **Evidência:** Ocorrência #25 (Escorregamento de escada).
*   **Análise de Conformidade:**
    *   *Ementa 135267-9 (NR-35):* Falha no sistema de ancoragem (Peso 4).
    *   *Infração Operacional:* Falha de procedimento (Peso 3).
*   **Avaliação Quantitativa:**
    *   Soma Pesos: 7
    *   Fator: 1.25
    *   Score Final: **8.75**
*   **Classificação:** **CRÍTICO (Nível 20)** - *Severidade Catastrófica*.

#### **Risco 03: Queda de Objetos**
*   **Fonte Geradora:** Ferramentas manuais soltas.
*   **Evidência:** Ocorrência #33 (Queda de alicate).
*   **Avaliação Quantitativa:** Score **3**.
*   **Classificação:** **MODERADO (Nível 9)**.

---

## 5. PLANO DE AÇÃO ESTRUTURADO (5W2H)

| ID | O Que (Ação) | Por Que (Motivo) | Quem (Resp.) | Quando (Prazo) | Onde (Local) | Como (Procedimento) | Quanto (Custo Est.) |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **PA-01** | **Treinamento NR-10** | Regularizar equipe (Auxiliar s/ curso, Líder vencido). | RH / SESMT | **IMEDIATO** | Centro de Treinamento | Matrícula em curso presencial (40h Básico + 40h SEP). | R$ 1.500,00 |
| **PA-02** | **Compra de EPIs (Luvas)** | Proteção contra choque na Zona Controlada. | Compras | 05 Dias | Almoxarifado | Aquisição de Luvas Isolantes Classe 0 + Luvas de Cobertura. | R$ 800,00 |
| **PA-03** | **Kit de Ancoragem** | Evitar escorregamento da escada. | SESMT | 07 Dias | Operação | Implementar fitas de poste e calços de borracha obrigatórios. | R$ 300,00 |
| **PA-04** | **Talabartes de Ferramenta** | Prevenir queda de objetos. | SESMT | 10 Dias | Operação | Uso de *tool lanyards* em todas as chaves e alicates. | R$ 200,00 |
| **PA-05** | **Detector de Tensão** | Identificar fugas de corrente (Ocorrência #12). | Engenharia | 15 Dias | Operação | Teste prévio no poste antes da subida. | R$ 400,00 |

---

## 6. PLANO DE RESPOSTA A EMERGÊNCIAS (PAE)

### 6.1. Cenário: Queda com Suspensão Inerte
**Objetivo:** Resgatar a vítima em menos de **10 minutos** para evitar trauma de suspensão.

**Fluxograma de Resposta:**
1.  **Alerta:** Auxiliar de solo identifica a queda e isola a área.
2.  **Acionamento:** Liga para **193 (Bombeiros)** e **SAMU (192)**. Informa: "Queda de altura, vítima suspensa pelo cinto".
3.  **Primeira Resposta (Se seguro):**
    *   Se houver risco elétrico: **NÃO TOCAR NA VÍTIMA/ESCADA**. Aguardar concessionária.
    *   Se sem risco elétrico: Tentar posicionar a escada para que a vítima apoie os pés (alívio da pressão nas pernas).
4.  **Monitoramento:** Manter contato verbal com a vítima até a chegada do socorro.

### 6.2. Recursos Mínimos
*   01 Kit de Primeiros Socorros por veículo (Item obrigatório).
*   Lista de telefones de emergência no painel.

---

## 7. MONITORAMENTO E INDICADORES (KPIs)

A eficácia do PGR será medida trimestralmente através dos seguintes indicadores:

| Indicador | Fórmula | Meta | Frequência |
| :--- | :--- | :--- | :--- |
| **Conformidade Legal (Treinamento)** | $(Nº Colab. Treinados / Total Colab.) \times 100$ | **100%** | Mensal |
| **Taxa de Inspeção de EPI** | $(Inspeções Realizadas / Programadas) \times 100$ | 100% | Mensal |
| **Redução de Ocorrências** | Nº Ocorrências Trimestre Atual vs Anterior | **0** | Trimestral |

---

## 8. ANEXOS E FORMULÁRIOS

### 8.1. Checklist de Verificação Diária (Modelo)

**Veículo/Equipe:** __________________ **Data:** ___/___/___

| Item | Verificação | OK | NOK | Obs |
| :--- | :--- | :--- | :--- | :--- |
| **1. Escada** | Borrachas da base íntegras? | [ ] | [ ] | |
| | Degraus sem trincas? | [ ] | [ ] | |
| | Fita de ancoragem disponível? | [ ] | [ ] | |
| **2. EPIs** | Cinto paraquedista inspecionado? | [ ] | [ ] | |
| | Luvas isolantes dentro da validade (teste)? | [ ] | [ ] | |
| | Capacete com jugular fixada? | [ ] | [ ] | |
| **3. EPCs** | Cones de sinalização disponíveis? | [ ] | [ ] | |
| | Detector de tensão funcional? | [ ] | [ ] | |

**Assinatura do Líder:** _________________________________

---
**Responsável pela Elaboração:**
Engenheiro de Segurança do Trabalho
Registro Profissional: XXXXXX
Data: 05/02/2026
