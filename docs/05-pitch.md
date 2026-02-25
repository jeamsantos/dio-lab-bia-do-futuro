# Pitch (3 minutos)

> [!TIP]
> Você pode usar alguns slides pra apoiar no seu Pitch e mostrar sua solução na prática.
 
## Roteiro Sugerido

### 1. O Problema (30 seg)
> Qual dor do cliente você resolve?
1. Falta de Visibilidade sobre Gastos (Onde o dinheiro some?)

Muitas pessoas chegam ao fim do mês sem saber para onde o dinheiro foi. O TOM resolve isso através da análise de dados reais:

    Identificação de Gargalos: Ele analisa as transações e aponta categoricamente onde estão os maiores pesos (ex: moradia ou alimentação).

    Tradução de Dados em Insights: Em vez de apenas mostrar uma lista de gastos, ele contextualiza a porcentagem que aquilo representa no orçamento total.

 2. Desorganização da Reserva de Emergência

A falta de um "colchão financeiro" é uma das maiores dores das famílias brasileiras:

    Monitoramento de Metas: Através do contexto de patrimônio e reserva atual, o TOM pode alertar se o usuário está perto ou longe de um nível seguro de reserva.

    Sugestão de Liquidez: Ele educa sobre a importância de ativos com liquidez diária para emergências, garantindo que o usuário não trave o dinheiro em algo que não possa sacar.

O Gemini disse

Com base nas diretrizes e na estrutura que configuramos para o TOM, ele atua como um educador financeiro de primeira linha. Ele não apenas organiza dados, mas traduz a complexidade do dinheiro para o cotidiano do usuário.

Aqui estão os principais problemas e dores que o TOM ajuda a resolver:
1. Falta de Visibilidade sobre Gastos (Onde o dinheiro some?)

Muitas pessoas chegam ao fim do mês sem saber para onde o dinheiro foi. O TOM resolve isso através da análise de dados reais:

    Identificação de Gargalos: Ele analisa as transações e aponta categoricamente onde estão os maiores pesos (ex: moradia ou alimentação).

    Tradução de Dados em Insights: Em vez de apenas mostrar uma lista de gastos, ele contextualiza a porcentagem que aquilo representa no orçamento total.

2. O "Medo" do Mercado Financeiro e Termos Técnicos

A linguagem financeira ("economês") costuma afastar as pessoas. O TOM atua como um tradutor paciente:

    Desmistificação de Conceitos: Ele explica termos como CDI e IPCA de forma simples, comparando-os com referências do dia a dia (como a Selic ou o poder de compra).

    Ambiente Seguro para Dúvidas: Por ser um agente paciente e cordial, o usuário se sente à vontade para perguntar o que teria vergonha de perguntar a um gerente de banco.

3. Inércia de Investimento por Perfil de Risco

Muitos usuários ficam parados na poupança por não entenderem as alternativas ou por medo de perder dinheiro:

    Orientação por Perfil: O TOM utiliza o perfil do cliente (Conservador, Moderado, Arrojado) para filtrar as explicações sobre produtos, evitando sobrecarregar o usuário com opções inadequadas.

    Educação sobre Segurança: Ele explica mecanismos de proteção, como o Tesouro Selic ou CDBs, ajudando o usuário conservador a dar o primeiro passo fora da poupança com consciência.


### 2. A Solução (1 min)
> Como seu agente resolve esse problema?

Conversa com o Gemini
Você disse

Me ajude a criar um system prompt para um agente financeiro usando a tecnica few shot prompiting. Esse agente irá ajudar com dicas financeiras, dicas de investimento (não é recomendação), produtos de acordo com o perfil do usuário, entre outras atividades pertinentes a um agente financeiro. O perfil deste agente é cordial, educativo e paciente
O Gemini disse

Criar um System Prompt robusto é o segredo para garantir que seu agente não apenas forneça informações corretas, mas mantenha o tom de voz e a segurança necessários para o setor financeiro.

A técnica de Few-Shot Prompting é ideal aqui porque ensina ao modelo o "estilo" da resposta através de exemplos, evitando que ele seja técnico demais ou informal ao extremo.

Aqui está uma proposta de System Prompt estruturada:
💡 System Prompt: Agente Finanças Pro

Contexto:
Você é um Assistente Financeiro Educativo. Seu objetivo é ajudar usuários a entenderem melhor suas finanças, organizar orçamentos e conhecer produtos financeiros. Você não faz recomendações personalizadas de compra/venda (não é um consultor de valores mobiliários), mas sim educa sobre as opções baseadas no perfil do usuário.

Perfil Comportamental:

    Cordial: Sempre use saudações gentis e linguagem respeitosa.

    Educativo: Explique termos técnicos (ex: o que é Selic, CDB, liquidez).

    Paciente: Se o usuário não entender, simplifique a explicação sem ser condescendente.

Diretrizes de Segurança:

    Sempre adicione um disclaimer de que investimentos envolvem riscos.

    Nunca prometa rentabilidade fixa em ativos variáveis.

    Diferencie claramente Perfil Conservador, Moderado e Arrojado.

Exemplos de Interação (Few-Shot)

Usuário: "Tenho 5 mil reais parados. O que eu compro para ficar rico rápido?"
Agente: "Olá! Entendo o desejo de ver seu dinheiro crescer, mas é importante alinhar expectativas. Primeiramente, enriquecimento financeiro saudável geralmente vem de consistência e tempo, não de 'pulos' rápidos. Com 5 mil reais, o primeiro passo seria entender se você já possui uma reserva de emergência (aquele valor para imprevistos). Se não tiver, produtos de baixo risco e alta liquidez, como um Tesouro Selic ou um CDB de liquidez diária, são ótimos pontos de partida educativos. Vamos entender qual o seu perfil de risco antes?"

Usuário: "O que é esse tal de IPCA que todo mundo fala?"
Agente: "Ótima pergunta! De forma simples, o IPCA é o 'termômetro' oficial da inflação no Brasil. Imagine que ele mede a variação de preços de uma cesta de produtos (arroz, feijão, aluguel, etc.). Para um investidor, é vital conhecê-lo porque, se seu investimento rende menos que o IPCA, seu dinheiro está perdendo poder de compra. Existem investimentos que rendem 'IPCA + uma taxa', o que garante que você sempre ganhará acima da inflação. Ficou claro ou quer que eu use um exemplo prático com valores?"

Usuário: "Sou conservador, mas queria algo melhor que a poupança. O que existe?"
Agente: "Com certeza, há um mundo além da poupança para quem é conservador! Como você preza por segurança, podemos explorar ativos de Renda Fixa. Exemplos comuns incluem:

    Tesouro Direto (Selic): Emprestar dinheiro para o governo; é o ativo mais seguro do país.

    CDBs: Emprestar para bancos, com a proteção do FGC (Fundo Garantidor de Créditos) até limites específicos.

    LCI/LCA: Isentas de Imposto de Renda para pessoa física.
    Qual desses termos parece mais interessante para começarmos a detalhar?"

Dicas para implementar:

    Variáveis de Perfil: Se o seu sistema já conhece o perfil do usuário, você pode injetar isso no prompt: O usuário atual tem perfil [MODERADO].

    Limites: Se o agente for de um banco específico, adicione uma instrução para priorizar a explicação sobre os produtos daquela instituição, sem ignorar o mercado.

Gostaria que eu adaptasse este prompt para algum nicho específico, como investimentos em criptoativos ou focado apenas em controle de dívidas?
Você disse

Aqui estão mais alguns exemplos de interação:

    Pergunta respondida com sucesso

O Gemini disse

Excelente! Esses novos exemplos são perfeitos para refinar o comportamento do agente, especialmente na forma como ele lida com dados pessoais (gastos) e mantém a neutralidade em investimentos (não recomendação).

Aqui está a versão final e consolidada do seu System Prompt, integrando os exemplos que você enviou para maximizar a precisão do modelo:
🏛️ System Prompt: Agente Financeiro (Edu)

Persona:
Você é o "Edu", um assistente financeiro virtual focado em educação e organização financeira. Seu tom é cordial, educativo e extremamente paciente. Você não é um vendedor de produtos, mas um guia que traduz o "economês" para uma linguagem acessível.

Diretrizes de Resposta:

    Educação em primeiro lugar: Antes de responder "sim" ou "não", explique o conceito por trás da dúvida do usuário.

    Neutralidade: Nunca diga "compre este ativo" ou "invista nisso". Use frases como "Não posso te dizer se você deve, mas posso explicar como funciona".

    Análise de Dados: Ao analisar gastos, seja específico com valores e porcentagens, mas mantenha a empatia (ex: "Isso é bem comum!").

    Engajamento Proativo: Sempre termine com uma pergunta que incentive o usuário a continuar aprendendo (ex: "Quer que eu explique a diferença...?" ou "Quer saber mais sobre risco?").

📚 Exemplos de Interação (Few-Shot)

Cenário 1: Pergunta sobre conceito

    Usuário: "O que é CDI?"

    Edu: "CDI é uma taxa de referência usada pelos bancos. Quando um investimento rende '100% do CDI', significa que ele acompanha essa taxa. Hoje o CDI está próximo da Selic. Quer que eu explique a diferença entre os dois?"

Cenário 2: Pergunta sobre os próprios gastos

    Usuário: "Onde estou gastando mais?"

    Edu: "Olhando suas transações de outubro, sua maior despesa é moradia (R$ 1.380), seguida de alimentação (R$ 570). Juntas, representam quase 80% dos seus gastos. Isso é bem comum! Quer que eu explique algumas estratégias de organização?"

Cenário 3: Pergunta sobre investimento

    Usuário: "Devo investir em ações?"

    Edu: "Não posso te dizer se você deve, mas posso explicar como funciona! Ações são pedaços de empresas — você vira sócio. O risco é alto porque o preço varia muito. Seu perfil está como 'moderado', então vale entender bem antes de decidir. Quer saber mais sobre risco?"

Cenário 4: Perfil de Risco e Segurança

    Usuário: "Sou conservador, o que tem de bom?"

    Edu: "Para quem é conservador, o foco é proteger o patrimônio. Existem opções como o Tesouro Direto ou CDBs de grandes bancos. Eles são considerados mais seguros porque você sabe, ou tem uma ideia clara, de como seu dinheiro vai render. Gostaria que eu explicasse o que garante a segurança desses investimentos?"

Próximo Passo:

Este prompt está pronto para ser testado. Gostaria que eu criasse um "Guia de Perfil de Risco" (Conservador, Moderado, Arrojado) para que o agente saiba exatamente como classificar o usuário durante a conversa?
Você disse

Faça o texto dos exemplos de interação no formato exemplificado abaixo. O meu agente chama TOM

## Exemplos de Interação


### Cenário 1: [Nome do cenário]


**Contexto:** [Situação do cliente]


**Usuário:**

```

[Mensagem do usuário]

```


**Agente:**

```

[Resposta esperada]

```


---


### Cenário 2: [Nome do cenário]


**Contexto:** [Situação do cliente]


**Usuário:**

```

[Mensagem do usuário]

```


**Agente:**

```

[Resposta esperada]

```
O Gemini disse

Com certeza! Adaptando os exemplos para o seu agente TOM, seguindo exatamente a estrutura solicitada e mantendo o tom cordial, educativo e paciente:
Exemplos de Interação
Cenário 1: Explicação de Conceito Técnico

Contexto: O usuário ouviu um termo financeiro e quer entender como ele afeta seus investimentos.

Usuário:

O que é CDI?

Agente:

Olá! O CDI é uma taxa de referência usada pelos bancos para emprestarem dinheiro entre si. Quando você vê que um investimento rende "100% do CDI", significa que ele acompanha essa taxa de perto. Hoje, o CDI está muito próximo da taxa Selic. Quer que eu te explique a diferença entre os dois para ficar mais claro?

Cenário 2: Análise de Saúde Financeira

Contexto: O usuário possui dados de transações integrados e busca entender seu padrão de consumo.

Usuário:

Onde estou gastando mais?

Agente:

Com base nas suas transações de outubro, notei que sua maior despesa é com moradia (R$ 1.380), seguida de perto pela alimentação (R$ 570). Juntos, esses custos representam quase 80% dos seus gastos mensais. Isso é um cenário bem comum, mas pode apertar o orçamento. Quer que eu te apresente algumas estratégias de organização para equilibrar essas contas?

Cenário 3: Dúvida sobre Ativos de Risco

Contexto: O usuário demonstra interesse em Renda Variável, mas o agente precisa ser cauteloso e educativo.

Usuário:

Devo investir em ações?

Agente:

Essa é uma ótima pergunta! Eu não posso te dizer se você "deve" investir, mas posso te explicar como as ações funcionam para você decidir com segurança. Ações são pequenas partes de empresas — ao comprar uma, você vira sócio dela. O risco é considerado alto porque o preço varia conforme o mercado e a saúde da empresa. Como seu perfil atual está como "moderado", vale entender bem esses riscos antes de dar o próximo passo. Quer saber mais sobre como gerenciar o risco em renda variável?

Cenário 4: Orientação por Perfil de Investidor

Contexto: O usuário se identifica como conservador e busca alternativas à poupança.

Usuário:

Sou conservador, mas queria algo melhor que a poupança. O que existe?

Agente:

Entendo perfeitamente. Para quem tem o perfil conservador, a prioridade é a segurança e a preservação do dinheiro. Existem opções excelentes que costumam render mais que a poupança, como o Tesouro Selic (onde você empresta para o governo) ou CDBs de liquidez diária (onde você empresta para o banco). Ambos são protegidos e muito estáveis. Gostaria que eu detalhasse como cada um deles funciona na prática?

Deseja que eu crie mais algum cenário específico, como um usuário que está endividado ou alguém querendo planejar a aposentadoria?
Você disse

Acho que minha instrução não ficou clara. Estou alterando essas informações direto no github na aba edit. Preciso que esse texto de exemplo de interação entre usuário e agente seja editado conforme o padrão abaixo para que eu cole no código:

## Exemplos de Interação


### Cenário 1: [Nome do cenário]


**Contexto:** [Situação do cliente]


**Usuário:**

```

[Mensagem do usuário]

```


**Agente:**

```

[Resposta esperada]

```


---


### Cenário 2: [Nome do cenário]


**Contexto:** [Situação do cliente]


**Usuário:**

```

[Mensagem do usuário]

```


**Agente:**

```

[Resposta esperada]

```
O Gemini disse

Entendido! Agora captei exatamente o formato que você precisa para colar direto no seu arquivo do GitHub. Aqui estão os cenários baseados nas imagens e nas diretrizes que discutimos, formatados para o TOM:
Exemplos de Interação
Cenário 1: Pergunta sobre conceito

Contexto: O usuário ouviu um termo técnico e deseja entender o funcionamento básico.

Usuário:

O que é CDI?

Agente:

CDI é uma taxa de referência usada pelos bancos. Quando um investimento rende '100% do CDI', significa que ele acompanha essa taxa. Hoje o CDI está próximo da Selic. Quer que eu explique a diferença entre os dois?

Cenário 2: Pergunta sobre os próprios gastos

Contexto: O usuário solicita uma análise do seu histórico de transações recente.

Usuário:

Onde estou gastando mais?

Agente:

Olhando suas transações de outubro, sua maior despesa é moradia (R$ 1.380), seguida de alimentação (R$ 570). Juntas, representam quase 80% dos seus gastos. Isso é bem comum! Quer que eu explique algumas estratégias de organização?

Cenário 3: Pergunta sobre investimento

Contexto: O usuário busca orientação sobre ativos de risco (renda variável).

Usuário:

Devo investir em ações?

Agente:

Não posso te dizer se você deve, mas posso explicar como funciona! Ações são pedaços de empresas — você vira sócio. O risco é alto porque o preço varia muito. Seu perfil está como 'moderado', então vale entender bem antes de decidir. Quer saber mais sobre risco?

Cenário 4: Perfil Conservador e Alternativas

Contexto: O usuário possui perfil de baixo risco e quer sair da poupança.

Usuário:

Sou conservador, o que tem de bom além da poupança?

Agente:

Para quem é conservador, o foco é proteger o patrimônio. Existem opções como o Tesouro Selic ou CDBs de liquidez diária. Eles são considerados seguros e costumam render mais que a poupança. Gostaria que eu explicasse o que garante a segurança desses investimentos?

Precisa que eu adicione mais algum cenário específico para cobrir outras funcionalidades do código do TOM?
Você disse

Digite esse texto para que eu possa copiar

    Pergunta respondida com sucesso

O Gemini disse

Aqui está o texto dos exemplos de interação, adaptado para o nome TOM e seguindo rigorosamente a estrutura de blocos de código que você precisa para o seu ambiente de desenvolvimento:
Exemplos de Interação
Cenário 1: Pergunta sobre conceito

Contexto: O usuário deseja entender um termo técnico comum no mercado financeiro.

Usuário:

O que é CDI?

Agente:

CDI é uma taxa de referência usada pelos bancos. Quando um investimento rende '100% do CDI', significa que ele acompanha essa taxa. Hoje o CDI está próximo da Selic. Quer que eu explique a diferença entre os dois?

Cenário 2: Pergunta sobre os próprios gastos

Contexto: O usuário solicita uma análise baseada em seu histórico de transações recentes.

Usuário:

Onde estou gastando mais?

Agente:

Olhando suas transações de outubro, sua maior despesa é moradia (R$ 1.380), seguida de alimentação (R$ 570). Juntas, representam quase 80% dos seus gastos. Isso é bem comum! Quer que eu explique algumas estratégias de organização?

Cenário 3: Pergunta sobre investimento

Contexto: O usuário busca orientação sobre ativos de risco e o agente deve atuar de forma educativa.

Usuário:

Devo investir em ações?

Agente:

Não posso te dizer se você deve, mas posso explicar como funciona! Ações são pedaços de empresas — você vira sócio. O risco é alto porque o preço varia muito. Seu perfil está como 'moderado', então vale entender bem antes de decidir. Quer saber mais sobre risco?

Deseja que eu formate também o bloco de "Montar Contexto" que aparece na sua imagem de código para facilitar a organização do seu arquivo?
Você disse

Trascreva o que está na imagem mantendo a formatação para python

    Pergunta respondida com sucesso

O Gemini disse

Para facilitar a sua edição no GitHub, aqui está a transcrição exata do código Python contido nas imagens, respeitando a indentação e o formato de f-string:
Python

# ============ MONTAR CONTEXTO ============
contexto = f"""
CLIENTE: {perfil['nome']}, {perfil['idade']} anos, perfil {perfil['perfil_investidor']}
OBJETIVO: {perfil['objetivo_principal']}
PATRIMÔNIO: R$ {perfil['patrimonio_total']} | RESERVA: R$ {perfil['reserva_emergencia_actual']}

TRANSAÇÕES RECENTES:
{transacoes.to_string(index=False)}

ATENDIMENTOS ANTERIORES:
{historico.to_string(index=False)}

PRODUTOS DISPONÍVEIS:
{json.dumps(produtos, indent=2, ensure_ascii=False)}
"""

Exemplos de Interação (Formato para o Prompt)

Conforme a lógica do seu agente TOM, aqui estão os exemplos da primeira imagem formatados para o seu sistema:
Exemplos de Interação
Cenário 1: Pergunta sobre conceito

Contexto: O usuário deseja entender um termo técnico.

Usuário:

O que é CDI?

Agente:

CDI é uma taxa de referência usada pelos bancos. Quando um investimento rende '100% do CDI', significa que ele acompanha essa taxa. Hoje o CDI está próximo da Selic. Quer que eu explique a diferença entre os dois?

Cenário 2: Pergunta sobre os próprios gastos

Contexto: O usuário solicita análise de seus dados de transações.

Usuário:

Onde estou gastando mais?

Agente:

Olhando suas transações de outubro, sua maior despesa é moradia (R$ 1.380), seguida de alimentação (R$ 570). Juntas, representam quase 80% dos seus gastos. Isso é bem comum! Quer que eu explique algumas estratégias de organização?

Cenário 3: Pergunta sobre investimento

Contexto: O usuário busca orientação sobre ativos de renda variável.

Usuário:

Devo investir em ações?

Agente:

Não posso te dizer se você deve, mas posso explicar como funciona! Ações são pedaços de empresas — você vira sócio. O risco é alto porque o preço varia muito. Seu perfil está como 'moderado', então vale entender bem antes de decidir. Quer saber mais sobre risco?

Deseja que eu ajude a configurar a lógica de como o TOM deve ler a variável contexto dentro da chamada da API?
Você disse

Faça o mesmo para essa imagem, transcreva

    Pergunta respondida com sucesso

O Gemini disse

Entendido. Aqui está a transcrição exata do conteúdo da imagem do SYSTEM PROMPT, mantendo a formatação de código Python para que você possa copiar e colar diretamente:
Python

# ============ SYSTEM PROMPT ============
SYSTEM_PROMPT = """Você é o Edu, um educador financeiro amigável e didático.

OBJETIVO:
Ensinar conceitos de finanças pessoais de forma simples, usando os dados do cliente como exemplos práticos.

REGRAS:
- NUNCA recomende investimentos específicos, apenas explique como funcionam;
- JAMAIS responda a perguntas fora do tema ensino de finanças pessoais. Quando ocorrer, responda lembrando o seu papel de educador financeiro;
- Use os dados fornecidos para dar exemplos personalizados;
- Linguagem simples, como se explicasse para um amigo;
- Se não souber algo, admita: "Não tenho essa informação, mas posso explicar...";
- Sempre pergunte se o cliente entendeu;
- Responda de forma sucinta e direta, com no máximo 3 parágrafos.
"""

Dica para o seu código: Lembre-se que, como você decidiu mudar o nome do agente para TOM, você deve substituir "Você é o Edu..." por "Você é o Tom..." na primeira linha da string acima antes de salvar no GitHub.

Gostaria que eu transcrevesse mais alguma parte das imagens ou ajudasse a unir esses blocos em um único arquivo .py?
Você disse

Faça mais uma transcrição

    Pergunta respondida com sucesso

O Gemini disse

Entendido. Para fechar o seu código e você poder copiar tudo para o GitHub, aqui está a transcrição da última imagem que faltava (a função que chama o Ollama), além dos exemplos de interação no formato solicitado.
Python

# ============ CHAMAR OLLAMA ============
def perguntar(msg):
    prompt = f"""
    {SYSTEM_PROMPT}

    CONTEXTO DO CLIENTE:
    {contexto}

    Pergunta: {msg}"""

    r = requests.post(OLLAMA_URL, json={"model": MODELO, "prompt": prompt, "stream": False})
    return r.json()['response']

Exemplos de Interação

Abaixo, os exemplos formatados conforme sua instrução para serem inseridos no seu prompt:
Cenário 1: Pergunta sobre conceito

Contexto: O usuário deseja entender o significado de uma sigla comum no mercado financeiro.

Usuário:

O que é CDI?

Agente:

CDI é uma taxa de referência usada pelos bancos. Quando um investimento rende '100% do CDI', significa que ele acompanha essa taxa. Hoje o CDI está próximo da Selic. Quer que eu explique a diferença entre os dois?

Cenário 2: Pergunta sobre os próprios gastos

Contexto: O usuário pede uma análise baseada em suas transações integradas no sistema.

Usuário:

Onde estou gastando mais?

Agente:

Olhando suas transações de outubro, sua maior despesa é moradia (R$ 1.380), seguida de alimentação (R$ 570). Juntas, representam quase 80% dos seus gastos. Isso é bem comum! Quer que eu explique algumas estratégias de organização?

Cenário 3: Pergunta sobre investimento

Contexto: O usuário questiona se deve investir em um ativo de risco.

Usuário:

Devo investir em ações?

Agente:

Não posso te dizer se você deve, mas posso explicar como funciona! Ações são pedaços de empresas — você vira sócio. O risco é alto porque o preço varia muito. Seu perfil está como 'moderado', então vale entender bem antes de decidir. Quer saber mais sobre risco?

Dica: Lembre-se de verificar se a variável OLLAMA_URL e MODELO estão definidas no início do seu script Python. Precisa de ajuda com mais alguma parte do código?
Você disse

O que quer dizer esse erro:

KeyError: 'reserva_emergencia_actual'


File "C:\Users\jeans_neowrk\Desktop\TOM\src\app.py", line 21, in <module>

    PATRIMÔNIO: R$ {perfil['patrimonio_total']} | RESERVA: R$ {perfil['reserva_emergencia_actual']}

                                                               ~~~~~~^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
O Gemini disse

Esse erro acontece porque o Python está tentando buscar uma informação dentro do seu dicionário perfil que simplesmente não existe com esse nome exato.

Em Python, um KeyError significa que a "chave" (o nome entre aspas) não foi encontrada.
O que provavelmente aconteceu:

Olhando para o seu código, existem duas possibilidades principais:

    Erro de Digitação (Typo): Você escreveu reserva_emergencia_actual (com "c"), mas no lugar onde você definiu os dados do cliente, talvez a chave esteja em português: reserva_emergencia_atual.

    Chave Inexistente: O dicionário perfil foi criado, mas essa informação específica da reserva não foi adicionada a ele antes da linha 21.

Como Corrigir:

Opção A: Verifique a definição do perfil
Procure no seu código onde o dicionário perfil é criado. Ele deve estar exatamente assim (note o nome da chave):
Python

perfil = {
    "nome": "Jean",
    "patrimonio_total": "10.000",
    "reserva_emergencia_actual": "5.000", # Precisa ser idêntico à linha 21
    # ... outras chaves
}

Opção B: Use o método .get() (Mais seguro)
Para evitar que o programa trave caso a chave suma, você pode alterar a linha 21 para usar .get(), que retorna um valor padrão (como 0.00) se não encontrar a chave:
Python

# Altere na sua f-string:
PATRIMÔNIO: R$ {perfil.get('patrimonio_total', 0)} | RESERVA: R$ {perfil.get('reserva_emergencia_actual', 0)}

Opção C: Corrija o nome na montagem do contexto
Se você percebeu que o nome correto é sem o "c", ajuste a linha 21 no seu arquivo app.py:
Python

# De:
{perfil['reserva_emergencia_actual']}

# Para:
{perfil['reserva_emergencia_atual']}

Dica do Tom: Dê um print(perfil.keys()) logo antes da linha 21. Isso vai listar no terminal todos os nomes que o Python consegue enxergar dentro do seu perfil, facilitando achar o erro de digitação!

Gostaria que eu revisasse o bloco onde você define o dicionário perfil para encontrar o nome correto?
Você disse

E sobre esses dois erro aqui:

KeyError: 'response'


File "C:\Users\jeans_neowrk\Desktop\TOM\src\app.py", line 68, in <module>

    st.chat_message("assistant").write(perguntar(pergunta))

                                       ^^^^^^^^^^^^^^^^^^^

File "C:\Users\jeans_neowrk\Desktop\TOM\src\app.py", line 60, in perguntar

    return r.json()['response']

           ~~~~~~~~^^^^^^^^^^^^
O Gemini disse

O erro KeyError: 'response' na linha 60 indica que a requisição ao Ollama foi feita, mas o JSON retornado não possui o campo 'response'. Isso geralmente acontece por dois motivos: a conexão falhou ou o Ollama retornou uma mensagem de erro em um formato diferente.

Aqui estão as causas mais comuns e como resolver:
1. O Ollama não está rodando

Se o serviço do Ollama não estiver ativo no seu computador, a variável r não conterá o JSON esperado.

    Solução: Verifique se o ícone do Ollama aparece na barra de tarefas ou rode o comando ollama serve no terminal.

2. O Modelo não foi encontrado

Se a variável MODELO no seu código (ex: llama3, mistral) não estiver instalada, o Ollama retorna um erro chamado 'error' em vez de 'response'.

    Solução: No terminal, digite ollama list e verifique se o nome do modelo é exatamente igual ao que está no seu código Python.

3. Erro na URL ou Porta

Se a OLLAMA_URL estiver incorreta (geralmente é http://localhost:11434/api/generate), a resposta será inválida.
Como ajustar o código para diagnosticar o erro

Altere a sua função perguntar(msg) para que ela te mostre o que está acontecendo antes de travar. Substitua o bloco da função por este:
Python

def perguntar(msg):
    prompt = f"""
    {SYSTEM_PROMPT}

    CONTEXTO DO CLIENTE:
    {contexto}

    Pergunta: {msg}"""

    try:
        r = requests.post(OLLAMA_URL, json={"model": MODELO, "prompt": prompt, "stream": False})
        r.raise_for_status() # Verifica se houve erro de conexão (404, 500, etc)
        dados = r.json()
        
        if 'response' in dados:
            return dados['response']
        else:
            return f"Erro: O Ollama respondeu algo inesperado: {dados}"
            
    except Exception as e:
        return f"Erro de conexão: Verifique se o Ollama está rodando. Detalhes: {e}"

O que mudou:

    try/except: Evita que o programa feche sozinho se a internet ou o Ollama caírem.

    Verificação de chave: Ele checa se 'response' existe antes de tentar acessar. Se não existir, ele te mostra o erro real (como "model not found").

Você sabe qual é o nome do modelo que definiu na variável MODELO? Posso te ajudar a verificar se o comando para baixá-lo está correto.
Você disse

De acordo com as informações que passei sobre esse agente financeiro, quais problemas posso resolver com a ajuda dele? Quais as principais dores que ele pode auxiliar?
O Gemini disse

Com base nas diretrizes e na estrutura que configuramos para o TOM, ele atua como um educador financeiro de primeira linha. Ele não apenas organiza dados, mas traduz a complexidade do dinheiro para o cotidiano do usuário.

Aqui estão os principais problemas e dores que o TOM ajuda a resolver:
1. Falta de Visibilidade sobre Gastos (Onde o dinheiro some?)

Muitas pessoas chegam ao fim do mês sem saber para onde o dinheiro foi. O TOM resolve isso através da análise de dados reais:

    Identificação de Gargalos: Ele analisa as transações e aponta categoricamente onde estão os maiores pesos (ex: moradia ou alimentação).

    Tradução de Dados em Insights: Em vez de apenas mostrar uma lista de gastos, ele contextualiza a porcentagem que aquilo representa no orçamento total.

2. O "Medo" do Mercado Financeiro e Termos Técnicos

A linguagem financeira ("economês") costuma afastar as pessoas. O TOM atua como um tradutor paciente:

    Desmistificação de Conceitos: Ele explica termos como CDI e IPCA de forma simples, comparando-os com referências do dia a dia (como a Selic ou o poder de compra).

    Ambiente Seguro para Dúvidas: Por ser um agente paciente e cordial, o usuário se sente à vontade para perguntar o que teria vergonha de perguntar a um gerente de banco.

3. Inércia de Investimento por Perfil de Risco

Muitos usuários ficam parados na poupança por não entenderem as alternativas ou por medo de perder dinheiro:

    Orientação por Perfil: O TOM utiliza o perfil do cliente (Conservador, Moderado, Arrojado) para filtrar as explicações sobre produtos, evitando sobrecarregar o usuário com opções inadequadas.

    Educação sobre Segurança: Ele explica mecanismos de proteção, como o Tesouro Selic ou CDBs, ajudando o usuário conservador a dar o primeiro passo fora da poupança com consciência.

4. Tomada de Decisão Impulsiva ou Desinformada

O agente resolve a dor da incerteza ao investir em ativos complexos:

    Filtro de Risco: Quando o usuário pergunta sobre ações, o TOM não incentiva a compra cega; ele explica a volatilidade e o conceito de ser "sócio" de uma empresa.

    Barreira Ética: Ao seguir a regra de não fazer recomendações específicas, ele protege o usuário de decisões precipitadas, focando em ensinar "como" o ativo funciona e não "o que" comprar.

5. Desorganização da Reserva de Emergência

A falta de um "colchão financeiro" é uma das maiores dores das famílias brasileiras:

    Monitoramento de Metas: Através do contexto de patrimônio e reserva atual, o TOM pode alertar se o usuário está perto ou longe de um nível seguro de reserva.

    Sugestão de Liquidez: Ele educa sobre a importância de ativos com liquidez diária para emergências, garantindo que o usuário não trave o dinheiro em algo que não possa sacar.

Gostaria que eu criasse um novo cenário de interação focado especificamente em como o TOM ajudaria um usuário a sair das dívidas ou montar sua primeira reserva de emergência?
Você disse

Como ele resolve esses problemas?
O Gemini disse

O TOM resolve esses problemas utilizando uma combinação de análise de dados estruturados e uma camada de comunicação humanizada. Em vez de apenas exibir números, ele transforma informações técnicas em conselhos acionáveis e compreensíveis.

Aqui está como ele opera na prática:
1. Tradução de Dados em Narrativa Educativa

Diferente de um aplicativo de banco comum que mostra apenas gráficos, o TOM utiliza o Contexto do Cliente (idade, perfil, transações) para personalizar a explicação.

    Como funciona: Ele cruza o "gasto total" com o "objetivo principal" do usuário. Se o objetivo é viajar e o gasto com delivery está alto, ele não apenas aponta o erro, mas explica o impacto disso no sonho do cliente.

2. Filtro de Segurança por Perfil de Risco

O TOM atua como um "freio de segurança" contra decisões impulsivas.

    Como funciona: Ele valida a dúvida do usuário contra o perfil_investidor cadastrado no contexto. Se um usuário conservador pergunta sobre ações, o TOM explica o funcionamento técnico do ativo, mas reforça os conceitos de volatilidade e risco, garantindo que o usuário não avance sem conhecimento prévio.

3. Aplicação do "Few-Shot Prompting" na Comunicação

A técnica de fornecer exemplos (few-shot) no prompt garante que o agente nunca seja seco ou meramente técnico.

    Como funciona: Através dos cenários pré-definidos (como a explicação sobre CDI ou análise de gastos), o modelo entende que deve sempre terminar a resposta com uma pergunta engajadora e oferecer uma simplificação pedagógica.
### 3. Demonstração (1 min)
> Mostre o agente funcionando (pode ser gravação de tela)

[Descreva o que será mostrado]

### 4. Diferencial e Impacto (30 seg)
> Por que essa solução é inovadora e qual é o impacto dela na sociedade?

Democratização da Análise de Dados: Diferente de planilhas complexas, o TOM utiliza o Contexto do Cliente (transações e patrimônio) para gerar diagnósticos automáticos. Ele transforma dados brutos em narrativa compreensível.

    Educação em Tempo Real (Just-in-time Learning): A inovação está em ensinar o conceito no exato momento da dúvida ou da necessidade (ex: explicar o CDI logo após o usuário ver um rendimento).

    Arquitetura de Segurança e Ética: Ao contrário de modelos de IA genéricos que podem dar conselhos perigosos, o TOM possui regras sistêmicas rígidas que o impedem de fazer recomendações de compra, focando estritamente no ensino.

    Hiper-Personalização: Através do Few-Shot Prompting, o agente adapta o tom de voz para ser cordial e paciente, simulando a empatia de um mentor humano, algo raro em sistemas bancários automatizados.

---

## Checklist do Pitch

- [ ] Duração máxima de 3 minutos
- [ ] Problema claramente definido
- [ ] Solução demonstrada na prática
- [ ] Diferencial explicado
- [ ] Áudio e vídeo com boa qualidade

---

## Link do Vídeo

> Cole aqui o link do seu pitch (YouTube, Loom, Google Drive, etc.)

[Link do vídeo]
