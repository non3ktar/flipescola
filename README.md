# FlipEscola - Conversor de PDF para Flipbook Premium

O **FlipEscola** é uma ferramenta de alta performance, minimalista e elegante, projetada para converter arquivos PDF em livros digitais interativos (Flipbooks) com animações 3D realistas. Desenvolvido com foco na experiência do usuário e na simplicidade, é ideal para professores e estudantes que desejam apresentar documentos de forma imersiva.

## 💎 Diferenciais
- **Aesthetic Premium**: Design minimalista com Glassmorphism e tipografia moderna.
- **Processamento 100% Local**: Seus arquivos nunca saem do seu computador. A conversão é feita inteiramente no navegador.
- **Interface Otimizada**: Barra de controles fixada na base, deixando o topo livre para leitura.
- **Download de PDF Duplo**: Permite exportar o livro no formato de páginas duplas (spread), pronto para visualização panorâmica.
- **Leve e Veloz**: Construído com HTML5, Tailwind CSS e Vanilla JavaScript, sem frameworks pesados.

## 🛠️ Stack Tecnológica
- **PDF.js**: Motor de renderização de PDFs da Mozilla.
- **Page-flip.js**: Biblioteca de animação 3D de páginas.
- **jsPDF**: Gerador de arquivos PDF para exportação.
- **Tailwind CSS**: Estilização moderna e responsiva.
- **Lucide Icons**: Conjunto de ícones minimalistas.

## 🚀 Como Executar
1. Clone este repositório.
2. Abra o arquivo `index.html` em qualquer navegador moderno.
3. Se desejar rodar via servidor local (recomendado para performance):
   ```bash
   npx serve .
   ```
4. Acesse `http://localhost:3000`.

## 📖 Como Usar
1. Clique no botão **"SELECIONAR"** no centro da tela.
2. Escolha seu arquivo PDF.
3. Aguarde o processamento das páginas (barra de progresso no centro).
4. Use as setas no rodapé ou o mouse para folhear o livro.
5. Clique em **"PDF DUPLO"** se desejar baixar a versão em páginas abertas.

## 📜 Histórico de Modificações
- **v1.0**: Implementação inicial com React (Vite).
- **v2.0**: Migração para Standalone (Vanilla JS) para maior estabilidade e performance.
- **v2.1**: Ajuste de UI (Minimalismo), redução de fontes e transferência da barra de controles para o rodapé.
- **v2.2**: Lançamento oficial no repositório FlipEscola.

---
Desenvolvido com carinho para o **Professor Sérgio** • Salinas da Margarida, Bahia, Brasil.
"Vibe Coding: Fast, fluid, aesthetic, and functional."
