# LayoutDTG
  Componente de DataGridView para reutilização em qualquer formulario Windows Forms.
  As cores padrão são: 
  
![Layout padrão](https://github.com/guilherme-beltran/LayoutDTG/assets/14238319/b289a6df-9bda-4e67-9e2a-ffc41a582414)

# Como utilizar?

  Para utilizar o componente basta adicionar uma referência a classe LayoutDataGridView que está no namespace 

    LayoutDTG.LayoutDataGridView

# Gerando o Layout

Para gerar o layout basta chamar o método GerarLayoutDataGridView informando o DataGridView que será customizado.

  Você tem a opção de informar apenas o DataGridView:

    LayoutDTG.LayoutDataGridView.GerarLayoutDataGridView(DataGridView dataGridView)

  Caso deseje alterar apenas a cor de fundo da coluna e a cor de fundo da letra, basta passar a cor por parâmetro:

    LayoutDTG.LayoutDataGridView.GerarLayoutDataGridView(DataGridView dataGridView, Color corFundoColunaSelecionadaOuNao, Color corLetraColunaSelecionadaOuNao)

  Ainda é possivel personalizar mais!

    LayoutDTG.LayoutDataGridView.GerarLayoutDataGridView(DataGridView dataGridView, Color corFundoColunaSelecionada, Color corLetraColunaSelecionada, Color corFundoColunaNaoSelecionada, Color corLetraColunaNaoSelecionada, Color corFundoLinhaSelecionada, Color corLetraLinhaSelecionada, Color corFundoLinhaNaoSelecionada, Color corLetraLinhaNaoSelecionada, Font fonteColuna = null, Font fonteLinha = null, int[] tamanhoColunas = null)

# Preenchendo o DataGridView

  Para preencher o DataGridView com os nomes das colunas:

    LayoutDTG.LayoutDataGridView.PreencherDataGridView(DataGridView dataGridView, string[] nomesColunas)

  Pode ainda exibir uma coluna ou oculta-la

    LayoutDTG.LayoutDataGridViewPreencherDataGridView(DataGridView dataGridView, string[] nomesColunas, bool[] colunaVisivel)

  E se quiser também pode alterar o tamanho da coluna:

    LayoutDTG.LayoutDataGridView.PreencherDataGridView(DataGridView dataGridView, string[] nomesColunas, bool[] colunaVisivel, int[] tamanhoColunas = null)

# Posso personaliza-lo?

Claro! Fique a vontade para personalizar o alerta conforme desejar! Sua contribuição será bem vinda!
  
