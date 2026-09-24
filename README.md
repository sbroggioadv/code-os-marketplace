# code-os — a bancada do escritório dentro do Claude Code

> ### AVISO — SOFTWARE PROPRIETÁRIO. NÃO É MIT. NÃO É LIVRE.
> Ferramenta **exclusiva dos mentorados da Mentoria iAPX (IA Combativa)**. O repositório é público só para o Claude Code conseguir instalar — visibilidade não é autorização.
> **Clonar, forkar, baixar ou instalar este repositório é declarar que você é mentorado ativo da iAPX.** Quem não é e faz isso responde civil, penal e administrativamente pelo uso não autorizado e pelo enriquecimento sem causa (Leis 9.609/98, 9.610/98 e 9.279/96; CC arts. 884–886). Leia a [LICENÇA](LICENSE.md) antes de qualquer coisa.

Plugin para Claude Code (app desktop ou terminal) que monta para o advogado a bancada do método Code-OS: **cliente-primeiro**, um `STATE.md` por caso, `FICHA.md` do que se sabe e do que se prova, cadeia de comando **Zeus → Gandalf → Chefe → Thor** (Suprema Corte R1–R4 do plugin da área + cinco camadas de defesa), **plugins IA Combativa** mapeados automaticamente (`/atualizar-os`), **repositório git privado no GitHub** sem precisar entender git (`/salvar`), modelos e jurisprudência do escritório, e `/me-ajuda` para qualquer dúvida.

Nada se move sem o advogado aprovar o plano; nada se apaga; segredos nunca entram na bancada. O conteúdo é do escritório; o plugin traz a mecânica.

## Instalar
**App Claude (desktop):** Configurações → Plugins → Marketplaces → Adicionar → `https://github.com/sbroggioadv/code-os-marketplace` → instalar `code-os`.

**Terminal:**
```bash
claude plugin marketplace add https://github.com/sbroggioadv/code-os-marketplace
claude plugin install code-os@code-os-marketplace
```
Abra a pasta do escritório (vazia, ou a antiga do Cowork, ou a do cowork-setup) no Claude Code e rode `/code-os`.

## Comandos
`/code-os` (montar · migrar · upgrade · auditar · atualizar · reconfigurar · doctor · suporte · conectar · restaurar) · `/zeus` · `/gandalf` · `/novo-cliente` · `/novo-projeto` · `/entregar` · `/salvar` · `/comecar` · `/encerrar` · `/me-ajuda` · `/atualizar-os` · `/modelos` · `/jurisprudencia` · `/lint-estrutura`.

## Requisitos
Python 3 (macOS já tem; Windows: python.org com "Add to PATH") · git · para o backup, conta no GitHub e o `gh` (opcional, guiado) · para `.docx` timbrado, `python-docx` (opcional). Mac e Windows. Rode `/code-os doctor` para conferir.

## Manual
`MANUAL.md` (e `MANUAL.pdf`) neste repositório. Suporte: SOS da mentoria com o pacote gerado por `/code-os suporte` (sem dado de cliente).

A IA é ferramenta. A responsabilidade técnica é do advogado.
