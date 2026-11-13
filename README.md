# Oot3D-PTBR-Remake-TriAevum 🇧🇷

Tradução brasileira de **The Legend of Zelda: Ocarina of Time 3D** para o TriAevum, com textos, nomes e elementos visuais atualizados ao padrão do Remake.

> **Projeto de fãs, não oficial e em desenvolvimento.** Esta é a primeira versão pública (v1.0.0). Embora a instalação tenha sido testada em uma versão limpa, ainda podem existir erros de tradução, inconsistências visuais e bugs. Relate os problemas na aba **Issues** deste repositório.

## Compatibilidade

**Testado em:** TriAevum `v0.8.0-beta.1.2-Windows-x64`.

Outras versões e plataformas ainda não foram validadas. O projeto não inclui o jogo original nem o TriAevum.

## Instalação

1. Obtenha a versão compatível do TriAevum e feche o programa.
2. Baixe o arquivo ZIP da **Release v1.0.0** e extraia-o.
3. Copie a pasta `OoT3D-PTBR` para `TriAevum/data/mods/`.
4. Copie `Instalar-PTBR.cmd` e `Instalar-PTBR.ps1` para a **raiz do TriAevum**.
5. Execute `Instalar-PTBR.cmd` e aguarde a confirmação.
6. Inicie o TriAevum.

O instalador procura `data/TriAevum.launch.json`, faz backup antes de modificar e ativa `--romfs-overlay`. Se não encontrar o JSON ou o mod, interrompe a instalação com uma mensagem de erro.

**As texturas dos letreiros e menus já estão no `.o3ro`.** Não é necessário instalar texturas na pasta AppData.

## O que mudou nesta versão?

- Revisão de nomes, itens, localidades e terminologia.
- Atualização de diálogos selecionados e nomes apresentados pela Navi.
- 56 letreiros personalizados.
- Mapas e menus atualizados, integrados ao arquivo `.o3ro`.
- Instalador automático com backup do arquivo de inicialização.

Consulte [CHANGELOG.md](CHANGELOG.md) para mais detalhes.

## Encontrou um erro?

Abra uma **Issue** e informe, se possível, o local ou momento do jogo, uma captura de tela, o comportamento observado e a versão do TriAevum.

## Créditos

Esta adaptação **não foi criada do zero**. A tradução de fãs original é creditada ao **Heroes of Time** e a adaptação utilizada como base ao **XandasL**. A revisão e os elementos visuais desta versão foram trabalhados por **Hadryn (Adriano Castro)**.

Leia [CREDITOS.md](CREDITOS.md). Agradecimentos aos demais colaboradores e aos desenvolvedores do TriAevum.

## Aviso legal

Projeto independente de fãs, sem vínculo ou endosso da Nintendo. Direitos de The Legend of Zelda pertencem aos respectivos titulares. A disponibilização pública dos arquivos derivados depende das permissões aplicáveis aos materiais originais; verifique-as antes de anexar o ZIP da tradução à Release.
