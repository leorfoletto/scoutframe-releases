# Política de Privacidade — ScoutFrame

**Versão 1.1 — vigente desde 2026-07-27**

Esta política explica quais dados pessoais o ScoutFrame trata, por quê, e quais
são os seus direitos, conforme a Lei Geral de Proteção de Dados (Lei 13.709/2018).

## 1. O ponto mais importante

**Seus vídeos, áudios, imagens e projetos nunca saem do seu computador.**

Todo o processamento — edição, anotações táticas, transcrição de narração e
renderização do vídeo final — acontece localmente, na sua máquina. O Fornecedor
não recebe, não armazena e não tem qualquer acesso ao seu material.

O que trafega pela internet é apenas o necessário para validar a sua licença,
conforme detalhado abaixo.

## 2. Controlador e contato

| | |
|---|---|
| Controlador | Leonardo Rezende Foletto — CPF 177.285.777-78 |
| Endereço | Contato pelo e-mail analyticsfutbr@gmail.com |
| Encarregado (DPO) | Atendimento por analyticsfutbr@gmail.com — agente de tratamento de pequeno porte, dispensado de indicar encarregado nos termos da Resolução CD/ANPD nº 2/2022, mantido este canal com o titular |
| Canal para assuntos de privacidade | **analyticsfutbr@gmail.com** |

## 3. Dados que tratamos

### 3.1 Dados de conta (você fornece)

| Dado | Finalidade | Base legal |
|---|---|---|
| E-mail | identificar a conta, enviar chave de licença, recuperação de senha e avisos contratuais | execução de contrato (art. 7º, V) |
| Nome | tratamento pessoal nas comunicações | execução de contrato (art. 7º, V) |
| Senha | autenticação — guardada apenas como hash PBKDF2, nunca em texto legível | execução de contrato (art. 7º, V) |

### 3.2 Dados de ativação (o aplicativo envia)

| Dado | Finalidade | Base legal |
|---|---|---|
| Identificador do dispositivo | limitar a licença a 2 dispositivos e coibir compartilhamento indevido. É um **hash SHA-256** derivado de um identificador do Windows com um segredo do aplicativo; não permite localizar você nem ler nada do computador | legítimo interesse — prevenção a fraude (art. 7º, IX) |
| Nome do dispositivo | permitir que você reconheça e libere seus próprios dispositivos na lista de ativações | legítimo interesse (art. 7º, IX) |
| Versão do aplicativo | compatibilidade, suporte e envio de avisos de atualização | legítimo interesse (art. 7º, IX) |
| Data/hora das validações | controlar a vigência da licença | execução de contrato (art. 7º, V) |

> O nome do dispositivo vem da configuração do Windows e, em alguns
> computadores, contém o nome da pessoa (ex.: "DESKTOP-JOAO"). Você pode
> renomear o computador no Windows se preferir não informá-lo.

### 3.3 Dados de pagamento

Assinaturas são processadas por plataforma de pagamento externa. **O Fornecedor
não recebe nem armazena números de cartão.** Recebemos da plataforma apenas a
confirmação do pagamento, o e-mail do comprador, o plano e o identificador da
assinatura, para liberar e manter a licença ativa.
Base legal: execução de contrato (art. 7º, V).

### 3.4 O que NÃO coletamos

Não há telemetria de uso, rastreamento de comportamento, publicidade,
identificadores de marketing nem venda de dados. Não coletamos localização.
Não usamos seus dados para treinar modelos de inteligência artificial.

## 4. Conexões que o aplicativo faz

| Destino | Quando | O que envia |
|---|---|---|
| Servidor de licenciamento do ScoutFrame (Cloudflare) | ao abrir o app e periodicamente | dados da seção 3.2 |
| Cloudflare Workers/D1 | hospedagem do servidor de licenciamento | — |
| Brevo | envio de e-mails transacionais (chave, recuperação de senha) | e-mail e nome |
| Plataforma de pagamento | ao contratar/renovar | dados da seção 3.3 |
| Hugging Face | **apenas se** você ativar as legendas automáticas | download do modelo de transcrição. A transcrição em si roda offline, no seu computador |

O aplicativo **não** carrega fontes, scripts ou imagens de servidores externos:
tudo é embarcado no instalador, e o programa funciona offline.

## 5. Compartilhamento com terceiros

Compartilhamos dados apenas com operadores necessários à prestação do serviço,
listados na seção 4, e somente no mínimo necessário. Também podemos compartilhar
dados mediante ordem judicial ou requisição de autoridade competente.

**Transferência internacional (art. 33 da LGPD):** Cloudflare, Brevo e a
plataforma de pagamento podem processar dados fora do Brasil. A transferência é
necessária para a execução do contrato com você (art. 33, II, "d" e art. 33, V) e
esses fornecedores adotam cláusulas contratuais de proteção de dados.

## 6. Por quanto tempo guardamos

| Dado | Prazo |
|---|---|
| Conta e licença | enquanto a conta existir |
| Registros de ativação | enquanto a licença existir, e por até 6 meses após o encerramento |
| Registros de pagamento | pelo prazo exigido pela legislação fiscal e civil (até 5 anos) |
| Tokens de recuperação de senha | expiram em poucas horas e são descartados após o uso |

Encerrada a conta, os dados são apagados ou anonimizados, ressalvada a guarda
obrigatória por lei (art. 16 da LGPD).

## 7. Seus direitos (art. 18 da LGPD)

Você pode, a qualquer momento, pedir: confirmação de tratamento; acesso aos
dados; correção de dados incompletos ou desatualizados; anonimização, bloqueio ou
eliminação de dados desnecessários; portabilidade; informação sobre
compartilhamento; e revogação do consentimento.

**Como exercer:** escreva para **analyticsfutbr@gmail.com** a partir do e-mail
cadastrado. Respondemos em até 15 dias.

> Observação: os dados de licença e de ativação são necessários para o
> funcionamento do produto. Se forem eliminados, a licença deixa de funcionar —
> o pedido de exclusão equivale a encerrar a conta.

Você também pode peticionar à Autoridade Nacional de Proteção de Dados (ANPD).

## 8. Segurança

Adotamos medidas técnicas compatíveis com o risco: tráfego cifrado por HTTPS,
senhas armazenadas apenas como hash PBKDF2-SHA256 com sal individual,
identificador de máquina armazenado apenas como hash, acesso administrativo
restrito com limite de tentativas, e princípio da coleta mínima.

**Registros de segurança:** para conter tentativas de acesso indevido ao painel
administrativo, registramos temporariamente o endereço IP de origem e a
contagem de tentativas falhas. Base legal: legítimo interesse na segurança dos
dados (art. 7º, IX, e art. 46). Esses registros são descartados após o
desbloqueio ou em até 30 dias.

Em caso de incidente de segurança com risco relevante, comunicaremos você e a
ANPD nos termos do art. 48 da LGPD.

## 9. Dados armazenados no seu computador

O aplicativo guarda localmente: seus projetos e vídeos, suas preferências
(tema, idioma) e o token da licença. Esses dados ficam na sua máquina, sob seu
controle, e podem ser apagados desinstalando o aplicativo e removendo a pasta de
dados do ScoutFrame.

## 10. Crianças e adolescentes

O ScoutFrame não se destina a menores de 18 anos. Não coletamos
intencionalmente dados de crianças e adolescentes.

## 11. Alterações desta política

Mudanças relevantes serão comunicadas por e-mail e/ou dentro do aplicativo com
antecedência de 30 dias. A versão vigente está sempre
disponível em **Ajuda → Avisos legais e licenças**.

---

Dúvidas sobre privacidade: **analyticsfutbr@gmail.com**
