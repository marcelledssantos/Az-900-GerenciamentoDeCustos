# Gerenciamento de Custos no Azure (AZ-900)

## 1. Introdução  
O gerenciamento de custos no Azure é essencial para planejar, monitorar e otimizar os gastos em nuvem.  
A prova **AZ-900** exige que o candidato compreenda como funcionam os modelos de preços, as ferramentas de estimativa e monitoramento de custos, além de práticas de otimização financeira.  

---

## 2. Modelos de Custos  

### 2.1 CapEx x OpEx  
- **CapEx (Capital Expenditure):** investimento em infraestrutura física (servidores, datacenters). Custo inicial alto e manutenção contínua.  
- **OpEx (Operational Expenditure):** modelo da nuvem. O cliente paga somente pelo uso dos recursos, sem necessidade de compra de hardware.  

### 2.2 Pagamento por Uso  
- O Azure adota o modelo de **pay-as-you-go**: paga-se apenas pelo que é consumido.  
- Isso permite maior flexibilidade e previsibilidade de gastos.  

### 2.3 Benefícios de Custos na Nuvem  
- Escalabilidade e elasticidade (paga mais apenas quando usa mais).  
- Evita gastos com infraestrutura ociosa.  
- Custos operacionais previsíveis com ferramentas de monitoramento.  

---

## 3. Fatores que Afetam Custos  
- **Tipo de serviço:** VMs, storage, banco de dados etc.  
- **Região:** preços variam conforme a região geográfica escolhida.  
- **Nível de desempenho:** instâncias menores custam menos, instâncias otimizadas custam mais.  
- **Tempo de uso:** cobrança pode ser por segundo, minuto ou hora.  
- **Licenciamento:** uso de licenças existentes (BYOL – Bring Your Own License) pode reduzir custos.  

---

## 4. Ferramentas de Estimativa e Planejamento  

### 4.1 Calculadora de Preços (Pricing Calculator)  
- Ferramenta online do Azure.  
- Permite simular custos com base nos serviços selecionados, região e tempo de uso.  
- Usada para **planejamento prévio** antes da implementação.  

### 4.2 Calculadora de Custo Total de Propriedade (TCO Calculator)  
- Compara os custos da nuvem Azure com os custos de manter infraestrutura local.  
- Mostra economia potencial ao migrar para a nuvem.  
- Útil para justificar decisões financeiras para gestores.  

---

## 5. Monitoramento de Custos  

### 5.1 Azure Cost Management  
- Ferramenta integrada ao portal do Azure.  
- Permite **visualizar, monitorar e analisar** os gastos em tempo real.  
- Gera relatórios de uso e tendências de consumo.  

### 5.2 Orçamentos (Budgets)  
- Configuração de limites de gastos.  
- Possibilidade de enviar **alertas** quando o orçamento atinge determinado percentual (ex.: 80%).  
- Não bloqueia recursos automaticamente, apenas avisa.  

### 5.3 Recomendações do Azure Advisor  
- Oferece sugestões para otimizar custos, como:  
  - Desligar ou redimensionar VMs subutilizadas.  
  - Migrar para opções mais econômicas.  
  - Adotar planos de desconto (Reservations, Spot VMs).  

---

## 6. Estratégias de Otimização de Custos  

### 6.1 Instâncias Reservadas (Reserved Instances)  
- Desconto em troca de compromisso de uso de 1 ou 3 anos.  
- Pode gerar até **72% de economia** em relação ao pay-as-you-go.  

### 6.2 Spot VMs  
- Utilizam capacidade ociosa da Microsoft a um custo muito menor.  
- Podem ser interrompidas a qualquer momento.  
- Indicadas para cargas de trabalho tolerantes a falhas.  

### 6.3 Uso de Tags  
- **Tags** ajudam a organizar e classificar recursos por departamento, projeto ou ambiente.  
- Facilitam relatórios de custos detalhados.  

### 6.4 Desligamento Automático de VMs  
- Evita gastos desnecessários em ambientes de teste e desenvolvimento.  

---

## 7. SLA e Impacto nos Custos  
- O **SLA (Service Level Agreement)** define a disponibilidade garantida por cada serviço.  
- Serviços com SLAs mais altos geralmente possuem custos maiores.  
- Combinações de serviços (ex.: redundância geográfica) também afetam o custo.  

---

## Conclusão  
O gerenciamento de custos no Azure envolve compreender os modelos de cobrança (**pay-as-you-go, reservas, Spot VMs**), utilizar ferramentas de **planejamento (Pricing Calculator, TCO Calculator)**, monitorar gastos com **Cost Management e Budgets** e aplicar boas práticas de otimização.  


