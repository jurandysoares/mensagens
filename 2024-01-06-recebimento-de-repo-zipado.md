# Recebimento de arquivo ZIP de repositório do Git

Olá! Em algumas disciplinas eu tenho adotado repositórios do Git hospedados no GitHub, e com um webhook configurado, como forma de acompanhar o desenvolvimento das atividades. Para recebê-las, no entanto, eu  solicito que seja anexado um arquivo com o repositório compactado no formato ZIP.  Recebo com frequência a pergunta: 

- *Professor, mas o senhor já tem o link do repositório hospedado no GitHub. Por que devo anexar o arquivo zipado [(sic)](https://www.dicio.com.br/sic/)?*

E eu respondo: 

- *Tem a ver com segurança da informação.*

Como o espaço aqui me permite, eu darei uma resposta mais elaborada. O arquivo no formato ZIP, anexado no GSA, nos garante mais integridade, autenticidade, não repúdio e irretroatividade. Para explicar estes conceitos, colo abaixo trecho que retirei [desse site](https://consultasaj.tjam.jus.br/WebHelp/id_seguranca_da_informacao.htm).

---

A segurança da informação está fundamentada, basicamente, nos seguintes itens:

- **Integridade:** a integridade visa assegurar que um documento não teve seu conteúdo alterado após ter sido assinado. Para isso, o sistema é capaz de detectar alterações não autorizadas no conteúdo. O objetivo é que o destinatário verifique que os dados não foram modificados indevidamente.
- **Autenticidade:** visa estabelecer a validade da transmissão, da mensagem e do seu remetente. O objetivo é que o destinatário possa comprovar a origem e autoria de um determinado documento.
- **Não repúdio:** visa garantir que o autor não negue ter criado e assinado o documento.
- **Irretroatividade:** visa garantir que o sistema não permita a geração de documentos de forma retroativa no tempo.

Um documento eletrônico é qualquer arquivo sobre o qual seja necessário agregar segurança segundo os itens acima relacionados. Esses requisitos de segurança podem ser atendidos por meio do uso de técnicas de certificação e assinatura digital e de protocolação eletrônica de documentos.

Fonte: <https://consultasaj.tjam.jus.br/WebHelp/id_seguranca_da_informacao.htm>

---

Espero ter esclarecido esta questão. Caso queira se aprofundar mais a respeito de segurança eletrônica, deixei alguns links.

- [Segurança da Informação](https://consultasaj.tjam.jus.br/WebHelp/id_seguranca_da_informacao.htm)
- [Lei nº 11.419, de 19 de dezembro de 2006, sobre a Informatização do Processo Judicial](https://www.planalto.gov.br/ccivil_03/_ato2004-2006/2006/lei/l11419.htm)
- [7.4 Git Tools - Signing Your Work](https://git-scm.com/book/en/v2/Git-Tools-Signing-Your-Work)
- [Signing commits - GitHub Docs](https://docs.github.com/en/authentication/managing-commit-signature-verification/signing-commits)
- [Handbook of Applied Cryptography](https://cacr.uwaterloo.ca/hac/)
