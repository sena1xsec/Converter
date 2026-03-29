# CONVERTER

Ferramenta em Python para **converter arquivos TXT, DOCX, PPTX e imagens para PDF**.

Script principal: `filepdf.py` (pasta `converter`)  

📂 Repositório: [https://github.com/senalxsec/Converter.git](https://github.com/senalxsec/Converter.git)

---

## Funcionalidades

- Converte **TXT, DOCX, PPTX e imagens** (JPG, PNG, BMP, TIFF) para PDF.  
- PDFs salvos na **Área de Trabalho com o mesmo nome do arquivo original**.  
- Busca automática de arquivos por nome nas pastas **Desktop, Documentos e Downloads**.  
- Conversão direta fornecendo o **caminho completo do arquivo**.  
- TXT: permite 1, 2 ou 3 linhas por célula.  
- Terminal limpo após cada ação, mantendo o menu organizado.  
- ASCII sempre visível no topo para aparência profissional.

---

## Estrutura do projeto
converter/
│
├─ filepdf.py        # Script principal
├─ requirements.txt  # Bibliotecas necessárias
└─ README.md         #Instruções 

 ---

## Instalação

1. Clone o repositório:

```bash
git clone https://github.com/senalxsec/Converter.git
2.	Entre na pasta do projeto:
cd converter
3. Instale as bibliotecas necessárias:
pip install -r requirements.txt

Uso:
1. Execute o script
python filepdf.py 
2. Menu.
•	Search e converter → Procura arquivos pelo nome nas pastas Desktop, Documentos e Downloads.
	•	Converter pelo caminho do arquivo → Converte diretamente pelo caminho completo.
	•	Sair → Encerra o programa.

	3.	Para TXT, escolha 1, 2 ou 3 linhas por célula.
	4.	PDFs convertidos serão salvos na Área de Trabalho com o mesmo nome do arquivo original.

Observações
	•	Funciona em Windows, Mac e Linux.
	•	Apenas arquivos TXT, DOCX, PPTX e imagens são suportados.
	•	PDFs já existentes não serão convertidos novamente.