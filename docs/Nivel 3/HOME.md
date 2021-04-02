# Nivel 3

![diagram](https://www.plantuml.com/plantuml/svg/0/hLRDRjiu4Bu7o3jmVOaBr1KQ9vSzrRMqhG7RSMEtmPuCMcPiRIbIbIWxxg8Fi-YX3v8NsncAKaXPSbEWFZWqPxxv-JW_UPCfcgeyvkTdVqGYvFcQaQrIIVQdvwLq_seJgMs-oZEMXb8e9jIhKCOUNQSH5JkU9xatlEhDE1NgusJiSQfOfk1gwRE4oqECWAImlcRtaM343pwDXZVJ-JEyg3m1HtqlGVDWf1U1j7SF6hqiIIDmvSKqKoprrco7ikp9pLytqyNWBfZVJ8BVwadVqJtBPCnwrnPfPLuU5PkSqxHC-qZ-3ztHLc5oK5ifMiMn51kvNhNBiozy2Rdjs95_Yn0Fqy-CmldPUF3tpSV5ycwqUByS1--2gTzzWVSNH4MACu9FoavyK7S61gNeXZm2IjbBqXaMfmuSpINXSaFNaWXAQCAZa8PKebW7qm6FymFuYRl9diBjx6w0GlO0f0lAyMo8xUZW0h2OmjDaRFbMvc9DqqCNVkx00wYQK-S5-VVyZC2diBqC7bIN9X5e36OZSWk9eU54Iaw08f1Sw4W0eByCgd8GKaKX2_aQ4pHdqYChbBFqG7H9FIXqIso_5V3IU2x1w9qOZsG8Q0grc_gh2j07XQcSVz44JF3r_HKUhOSkuLQA9VeAu_IdZfTRnfU-7P3jIeM9hJUsBTbwkgECvZTyZWQo4hgXsF-QhLdvurbqLL3awntCb3qzaEgoI0U-i9EQoAiq--rmXmtRdmCcFybHI1NT5wNyMhzKzRCbJoTD2trfeHz_F7v_IhAO20sFRA4nrCK-ubp39ZJY9ARfPwOYiJcDn0hneooXgKnIZPvFvgSXrrQeAfA2lCzrISxoR4k49IZDN1X37tAMipfbs0qMROsOUWINft1L8HovwpyVraHJ2_GRqTF2OQog3nR6c6Gmd40z16A3cmazfJ1m9dATmtGzsGzbfO2TozDsdAfskW6m_L_1OalS6ey6QyQ24vEc2EH8pKWkoYe0EwGSdzhMawKh8ouxIglfpZ8pgLmUnGQePepfKRmiPdTDeY_j2TiaTqPAaqAjlffKp2jKebBeGciLLpFKgdlr2xhNRXIugfqdXsY7DDpgFOn_gs6YN_c2D6ocWMOMzjBZV-LYEjAr8YZKZoRM4MIuPU7daT1_P6wSu8zU98X7YgFCzHfE6Iuq2cqGaoHbFPehcKPVZVMwPQZdmXmSNDSs4o3q8KCTQs_-OTp4HDFU1LMSXSq0gm5WkxxbSZMAwOPbjMthX5lLNn7qpDv6pQ5KY9PO48FzrTGOXKHVMhLWsjWILYGs8TtIg6auGfSrnusZLsUhPjFbg9Q_OzNLR2gouroRj6e1b7GyLOrZfi72KKiuWD9UczRvsHicrl1l-Fy0)

**Level 2: Container diagram**

Depois de entender como seu sistema se encaixa no ambiente geral de TI, uma próxima etapa realmente útil é ampliar o limite do sistema com um diagrama de contêiner. Um "contêiner" é algo como um aplicativo da web do lado do servidor, aplicativo de página única, aplicativo de desktop, aplicativo móvel, esquema de banco de dados, sistema de arquivos, etc. Essencialmente, um contêiner é uma unidade executável / implementável separadamente (por exemplo, um espaço de processo separado ) que executa código ou armazena dados.

O diagrama do Container mostra a forma de alto nível da arquitetura do software e como as responsabilidades são distribuídas por ela. Também mostra as principais opções de tecnologia e como os contêineres se comunicam. É um diagrama simples e focado em tecnologia de alto nível, útil para desenvolvedores de software e equipes de suporte / operações.
**Scope**: A single software system.

**Primary elements**: Recipientes dentro do escopo do sistema de software.
Elementos de suporte: Pessoas e sistemas de software diretamente conectados aos containers.

**Intended audience**: Pessoal técnico dentro e fora da equipe de desenvolvimento de software; incluindo arquitetos de software, desenvolvedores e equipe de operações / suporte.

**Notes**: Este diagrama não diz nada sobre cenários de implantação, clustering, replicação, failover, etc.