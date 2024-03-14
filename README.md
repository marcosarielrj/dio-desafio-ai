# Desafio Azure Cognitive Search

Foi utilizado o serviço de pesquisa lincado ao serviço de storage e utilizad Serviços de AI para retornar pesquisas 
de um banco de informações inseridos. Na pasta outputs encontrase o arquivo resultadopesquisa com a saida do mesmo.

# Desafio Language Studio
Foi utilizado o recurso Analyze sentiment and opinions utilizando o arquivo analise dentro de inputs,
gerando uma saida na pasta outputs com nome saida-analise1, saida-analise2 e saida-analise3.

# Desafio Speech Studio

Foi utilizado o Conversão de fala em texto em tempo real utilizando o arquivo audio 1 dentro de inputs
e dentro da pasta outputs está a saída no arquivo saidaaudio.

# Desafio Reconhecimento Facial e transformação de imagens em Dados no Azure ML

Dentro da pasta inputs estão as imagens usadas para o desafio, a imagem de legenda e ocr é a mesma.
Dentro da pasta outputs os resultados obtidos.

# Desafio Trabalhando com Machine Learning na Prática no Azure ML

Foi executado o passo a passo disponível hein

https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/01-machine-learning.html

![image](https://github.com/marcosarielrj/dio-desafio-ai/assets/28981742/dac9e89c-bcc2-47d7-8c87-04212462db79)


Microsoft Azure AI Fundamentals

Conceitos Fundamentais de AI
Prever resultados e reconhecer padrões com base em dados históricos
Extrair informações de fontes para obter conhecimento
Compreender a linguagem e participar de conversas - chatbots
Reconhecer eventos anormais e tomar decisões - desastres, mercado financeiro
Interpretar informações visuais - fotos, vídeos

Cargas de trabalhos comuns em AI
Machine Learning - Modelos preditivos baseados em dados e estatísticas, baseado em dados históricos, tentar prever comportamentos
Visão computacional - Capacidades de AI para interpretar o mundo visualmente por meio de câmeras, vídeos e imagens. Ex. Google Fotos identificar pessoas, reconhecer pessoas na multidão, reconhecimento facial, etc.
Processamento de linguagem natural - Capacidades da AI para que um computador interprete a linguagem escrita e falada e responda adequadamente. Ex. servidor de email verificar phishing, redes sociais filtrar comentários.
Inteligência de Documentos - Capacidades de AI que lidam com o gerenciamento, processamento e uso de grandes volumes de dados encontrados em formulários e documentos. Document Intelligent Studio
Mineração de conhecimento - Capacidade de AI para extrair informações de grandes volumes de dados muitas vezes não estruturados  para criar um armazenamento de conhecimento pesquisável - Ingerir, Enriquecer e Explorar 
AI Generativa - Recursos de IA que criam conteúdo original em vários formatos, incluindo linguagem natural, imagem, código e muito mais - Chat GPT.
Princípio de AI responsável
Imparcialidade - O preconceito pode afetar os resultados - Ex. um modelo de aprovação de empréstimo que discrimina por gênero, cor devido aos dados os quais foi treinado.
Confiabilidade e Segurança - Erros que podem causar danos - Um veículo autônomo sofre uma falha no sistema e causa colisão.
Privacidade e Segurança - Dados privados podem ser expostos - Um bot de diagnóstico médico é treinado usando dados confidenciais de pacientes que são armazenados de forma insegura.
Inclusão - As soluções podem não funcionar para todos - Um aplicativo preditivo não fornece saída de áudio para usuários com deficiência visual.
Transparência - Os usuários devem confiar em sistema complexo - Uma ferramenta financeira baseada em AI faz recomendações de investimento - em que se baseiam?
Responsabilidade - Quem é responsável pelas decisões baseadas na IA? Uma pessoa inocente é condenada por um crime com base em provas de reconhecimento facial - quem é o responsável? Deve-se deixar espaço para ação humana.

Fundamento do aprendizado de máquina

O que é aprendizado de máquina? 
Ciência de dados - informações, de modelos diferentes, de tipos de dados diferentes, diversas fontes
Engenharia de Software - Manipular e transcrever os dados
Microsoft Azure Machine Learning 

Tipos de aprendizado de máquina
Supervisionados - Os dados de treinamento incluem rótulos conhecidos
Regressão - o rótulo é um valor numérico, quantitativo - Ex número de sorvetes vendidos, depende do dia, temperatura, estoque, dados a serem alimentados.
Classificação - rótulo é uma categorização, quando for tratar valores, tomar decisões deve ser supervisionados.
 Binária - Label é ou não é uma classe - Ex. Prever se o paciente corre risco de diabetes com base em dados clínicos; Libera ou não empréstimos baseado no histórico e score.
Multiclasse - Label é uma das múltiplas classes - Preveja a espécie de um animal baseado em características; Filme - Preveja o gênero dos filmes baseado em características.

Não supervisionados 
Classificação - rótulo é uma categorização, não é conhecido, quando precisa rotular através de semelhanças sem especificidades 
Identifica semelhanças sem definir uma características específica, Agrupa antes de treinar, por similaridade.

Treinamento e avaliação de modelo

 
 
Dados de treinamentos - tipos de dados diferentes e de diversas origens, sempre crescentes, sempre devem ser atualizados
Depois aplica o algoritmo
Encapsula o Modelo
Gera as previsões
Avaliar os resultados - identificando possíveis inconsistências

Aprendizado profundo

Rede neural humana - as redes neurais artificiais buscam reproduzir como o cérebro humano se desenvolve 
Neurônios disparam em resposta a estímulos eletroquímicos, quando disparado o sinal é passado para todos os neurônios conectados
Redes neurais artificiais - Cada neuronio é uma funçao que opera com um valor de entrada(x) e um peso (w), a qual é envolvida em uma função de ativação que determina se a saída deve ser transmitida. 

 

Azure Machine Learning - é uma plataforma baseada em nuvem para aprendizado de máquina

Noções básicas do Azure

Armazenamento de Dados
Serviços de computação - Máquinas virtuais, servidores
Serviços de AI
Aprendizado de Máquina Azure - Uma plataforma para treinar, implantar e gerenciar modelos de aprendizado de máquina
Serviços de AI do Azure - Um conjunto de serviços que abrange visão, fala, linguagem, decisão e IA generativa
Recurso autônomos para serviços específicos 
Recurso geral de serviços de AI do Azure para vários serviços 
Consumidos por aplicativos via: Um endpoint REST (https://endereço); Uma chave de autenticação ou token de autorização.
Pesquisa Cognitiva do Azure - Extração, enriquecimento e indexação de dados para pesquisa inteligente e mineração de conhecimento. Coisas que implicam a AI - Volume de informações, tipos distintos de informações e expectativa do cliente.
Visão Computacional

Uma imagem é uma matriz de valores de pixels
Filtros são aplicados para alterar imagens

Redes Neurais Convolucionais

 
Imagens rotuladas são usadas para treinar o modelo
Camadas de filtros extraem mapas de recursos de cada imagem
Os mapas de recursos são reunidos
Os valores dos recurso são alimentados em uma rede neural totalmente conectada
A camada de saída produz um valor de probabilidade para cada rótulo de classe possível
Modelos Multimodais
	
 
Microsoft Azure AI Vision
Um modelo multimodal pode ser usado como modelo base para modelos adaptativos mais especializados.
Consegue identificar dentro do vídeo objetos, pessoas ações

Serviço de visão computacional no Azure

Análise de imagem
Marcação de imagens, legendas, personalização de modelos e muito mais
Reconhecimento Óptico de Caracteres (OCR)
Análise espacial
Detecção de rosto
Reconhecimento facial
Análise de imagem 4.0 com o AI Vision Service

Recursos:

Personalização do modelo
Ler textos de imagens
Detectar pessoas em imagens
Gerar legendas de imagens
Detectar objetos
Marcar recursos visuais
Corte Inteligente

Deteção de rostos com o Face Service - serviço pode ser usado por todos para:

Desfoque: quão desfocado está o rosto
Exposição: aspectos como Ruído: refere-se ao ruído visual da imagem
Características: utilização ou não de objetos: óculos, brincos.
Pose da cabeça: a orientação do rosto em um espaço 3D

Somente clientes gerenciados da Microsoft podem acessar os recurso para:
Correspondência de similaridade
Verificação de identidade

Lendo texto com reconhecimento óptico de caracteres (OCR) - detecta textos:

Impresso
Escrito à mão
Opções para extração rápida de texto de imagens ou análise assíncrona de documentos digitalizados maiores
Processamento de linguagem natural 

NER - Reconhecimento de Entidade Nomeada
Evento, Localização, Data
Detecção de PII e PHI
URL, Número de Telefone, Email, Organização
Detecção de Idioma
Análise de Sentimentos
Sentença de sentimento - positiva, negativa e neutra
Opiniões sobre  - comida, bebida, roupa
Opiniões sobre - serviço, produto
Respostas a perguntas - Chatbot
AI conversacional no Azure

Texto para fala
Conversão de fala para texto
Tradução de fala
Tradução de documentos
Tradução de texto
Tradução personalizada
Azure Language Studio
Analisa textos:
	“Passei férias maravilhosa na França”
	Idioma - Portugues
	Sentimento - 0,88(Positivo)
	Frases-chave: férias maravilhosas
	Entidades: França

Serviço de bot do Azure
Plataforma baseada em nuvem para desenvolvimento e gerenciamento de bots
Integração com AI Language e outros seriviços
Conectividade através de vários canais
Compreensão da linguagem coloquial
Reconhecimento e síntese de fala

Inteligência de Documentos de Ai do Azure - Document Intelligence

Análise de documentos:
Retorna representações de dados estruturados
Regiões de interesse e relacionamentos
Configurar opções de análise para analise gratuita e cobrada

Modelos pré-construidos:

Faturas
Recibos
Identificador
Reconhece e extrai pares de valores-chaves

Extraia informações de formulários digitalizados em formato de imagem ou PDF
Treine um modelo personalizado usando seus próprios formulários
Estúdio de Inteligência de Documentos
Usando uma abordagem sem código você pode explorar a funcionalidade usando seus exemplos e seus próprios documentos
Pesquisa cognitiva do Azure - Azure Cognitive Search - alimentada por Ai

O que é mineração de conhecimento?
Os dados são bloqueados em documentos, PDFs, notas manuscritas
A mineração de conhecimento encontra insights em escala

Soluções de Pesquisa Cognitiva do Azure
Azure Blob Storage containers
Azure Data Lake Storage Gen2
Azure Table Storage
Enriquecimento e índice de AI
Permite uma compreensão mais profunda
Visão, Processamento de lInguagem Natural, etc
A indexação torna o conteúdo pesquisável
Explorar
Pesquisa realizada em índices
Dentro dos aplicativos
Crie visualizações de dados
Enriquecimento de AI
O enriquecimento de AI torna o conteúdo mais útil para fins de pesquisa
O conteúdo enriquecido é criado por conjuntos de habilidades como
Reconhecer entidades no texto 
Traduzir texto 
Avaliar sentimentos
Um conjunto de habilidades produz documentos enriquecidos
Consumido durante a indexação
Os dados serializados são passados ao mecanismo de pesquisa para indexação
AI Generativa - OpenAI do Azure

Imita o comportamento humano usando aprendizado de máquina para interagir com o ambiente e executar tarefas sem instruções explícitas sobre o que gerar
Cria conteúdo original, utilizam linguagem natural e retornam respostas apropriadas em variedade de formatos
Geração de linguagem natural
Geração de código 
Geração de imagem

Modelos de Linguagem Grandes - Os aplicativos de AI generativas são alimentados por LLMs - Modelos de Linguagem Grandes - que são um tipo especializado de modelo de machine learning que você pode usar para executar tarefas de PLN - Processamento de linguagem natural
Determinar sentimento ou classificar de outra forma o texto em idioma natural
Resumir texto
Comparar várias fontes de texto quanto à similaridade semântica
Geração de nova linguagem natural
LLM - transformador
Um bloco codificador que cria representações semânticas do vocabulário de treinamento
Um bloco decodificador que gera novas sequências de linguagem 
O texto é tokenizado para que cada palavra ou frase seja representado por um token numérico exclusivo
Inserções - valores de vetor com várias dimensões - são atribuídos aos tokens
As camadas de atenção examinam cada token por vez e determinam valores incorporados que refletem os relacionamentos semânticos entre os tokens
No decodificador, essas relações são usadas para prever a sequência mais provável de tokens 
 
LLM - tokenização
A primeira etapa no treinamento de um modelo de transformador é decompor/particionar o texto de treinamento em tokens
Define um valor para cada palavra e reutiliza o mesmo valor ao invés da própria palavra 
LLM - inserções
As relações entre tokens são capturadas como vetores, conhecidos como inserções 
O quão próximo um token vai ficar próximo ao outro dentro das maiores probabilidades
LLM - atenção 
Capture a força das relações entre tokens usando a técnica da atenção
Ex. Meta - prever o próximo token após “Cachorro”
Represente “Ouvi um cachorro” como vetores
Atribua mais peso a “ouvi” - relacionado a barulho - e “cachorro” atributos de cachorros
Treinar através de repetição, elencando os melhores resultados

Copilot - são integrados a outros aplicativos e fornecem uma maneira para os usuários obterem ajuda com tarefas comuns a partir de um modelo generativo de AI
Os usuários empresariais podem usar copilotos para aumentar sua produtividade e criatividade com conteúdo gerado por AI
Engenharia de prompts - Aprimorar as respostas de AI generativa, aprimoramento de prompts
Os usuários - desenvolvedores, utilizadores - dos aplicativos podem aprimorar a qualidade das respostas da AI generativa usando linguagem direta, mensagens do sistema, exemplos e/ou dados de fundamentação
Linguagem direta - “Crie uma lista de 10 coisas a se fazer”
Fornecer exemplos - alimentar as LLMs
Dados básicos
	Serviço OpenAI do Azure
solução de nuvem da Microsoft para implantar, personalizar e hospedar LLMs.
Modelos de AI gerativa predefinidos 
Funcionalidades de personalização
Ferramentas integradas para detectar e mitigar casos de uso prejudiciais para que os usuários possam implementar a AI com responsabilidade
Segurança corporativa com RBAC - controle de acesso baseado em função - e redes privadas
Soluções - Estúdio de IA do Azure; API REST, SDKs com suporte e CLI do Azure
Modelos suportados pelo OpenAI
GPT 3.5 / 4 - compreender e gerar linguagem e códigos naturais
Incorporações - converter texto em formulário de vetor numérico 
DALL - E - podem gerar imagens originais a partir de linguagem natural
Planejar uma solução de IA generativa responsável
Identificar, Medir, Mitigar e Operar









