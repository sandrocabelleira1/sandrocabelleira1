# Olá, sou Sandro Cabelleira


## Desenvolvimento de aplicações web com IA


Desenvolvo aplicações web que conectam IA generativa, interfaces intuitivas e serviços em nuvem. Gosto de transformar necessidades concretas em experiências úteis, acompanhando o produto da ideia à implantação.


## Projetos em destaque


### [Xtreme Dr. X — assistente de instalação com IA](https://github.com/sandrocabelleira1/xtremeDr.X)


Aplicação para apoiar a instalação e o diagnóstico do Quickshifter Xtreme, com chat e análise de fotos e vídeos. Integra autenticação, persistência de dados, créditos e pagamentos.


**Aplicação publicada:** [experimentar o Xtreme Dr. X](https://studio--studio-6575887507-cfd43.us-central1.hosted.app/)


**Tecnologias:** Next.js, React, TypeScript, Genkit, Gemini, Firebase e Stripe.


**Destaques:** integração multimodal, operações protegidas no servidor e implantação no Firebase App Hosting conectado ao GitHub.


[Ver estudo de caso e arquitetura](https://github.com/sandrocabelleira1/xtremeDr.X)


### [MotoAI Assist — diagnóstico de motocicletas com IA](https://github.com/sandrocabelleira1/motoai-assist-case-study)


Protótipo que organiza marca, modelo e sintomas para apresentar causas prováveis, passos de verificação e ferramentas sugeridas. Também explora um assistente conversacional e a busca de oficinas próximas.


**Tecnologias:** Next.js, React, TypeScript, Genkit, Gemini 2.0 Flash e Zod.


[Ver estudo de caso](https://github.com/sandrocabelleira1/motoai-assist-case-study)


### [TuneAssist — ferramenta web para análise e edição de mapas ECU](https://github.com/sandrocabelleira1/TuneAssist)


Projeto voltado a organizar o fluxo de trabalho de análise de calibrações: carrega arquivos BIN e definições XDF, interpreta mapas e eixos, e oferece ferramentas para analisar dados de ensaio e editar valores com visualização tabular e gráfica. O código-fonte está em repositório privado; esta apresentação descreve as funcionalidades implementadas no projeto.


**Como funciona:** o usuário fornece um BIN e um XDF para localizar e interpretar mapas. Pode importar um CSV de log com RPM e Lambda ou inserir pontos manualmente, escolher Lambda-alvo e intensidade de correção e aplicar ajustes calculados aos mapas de combustível. As alterações podem ser revisadas, editadas ou revertidas antes de gerar um BIN modificado para download.


**Recursos:** análise de combustível por logs Lambda; comparação de ensaios de ignição; visualização em tabela, gráfico 2D e superfície 3D; edição de células e operações em massa (percentual, valor fixo, interpolação e restauração); configuração manual de eixos e endianness; download do BIN editado; backups de arquivos no Firebase Storage com metadados no Firestore.


**Tecnologias e serviços:** Next.js 15, React 18, TypeScript, Tailwind CSS, componentes Radix UI, PapaParse para CSV, Plotly.js e Recharts para visualização, Firebase Authentication, Cloud Firestore, Firebase Storage e integração de checkout com Mercado Pago.


**Nota técnica:** o fluxo de correção de combustível implementado calcula ajustes a partir dos dados fornecidos; a interface não constitui validação de calibração, teste em dinamômetro ou garantia de segurança mecânica. A validação do arquivo e da aplicação depende de revisão e testes apropriados pelo usuário.


## Tecnologias utilizadas nos projetos


| Área | Tecnologias |
| --- | --- |
| Aplicações web | TypeScript, React e Next.js |
| IA generativa | Gemini, Genkit e validação com Zod |
| Serviços e dados | Firebase Authentication, Firestore e Firebase Admin |
| Integrações | Stripe Checkout e webhooks |
| Interface e publicação | Tailwind CSS e Firebase App Hosting |


Os repositórios públicos apresentam os estudos de caso e as decisões técnicas. O código-fonte dos projetos permanece privado.


## Formação AWS


- **AWS Technical Essentials (Português)** — concluído em 17/10/2026. Certificado de conclusão de treinamento: [visualizar certificado em PDF](certificates/AWS-Technical-Essentials-2026.pdf). [Validar no AWS Skill Builder](https://skillbuilder.aws/learn/K8C2FNZM6X/aws-technical-essentials-portugus/3HVMQNBXYA)


## Interesses


Aplicações com IA generativa, experiências multimodais e integração de modelos em produtos web.
