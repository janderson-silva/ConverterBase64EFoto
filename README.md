## 🤝 Se este projeto te ajudou de alguma forma e você quiser apoiar o desenvolvimento, considere fazer uma doação via Pix:

**Chave Pix:** `8af2a30e-41c1-409a-8a35-b7a8a864b985`  
**Titular:** Janderson Aparecido da Silva

<p align="center">
  <img src="https://github.com/janderson-silva/Docs/blob/main/Pix/qrcode-pix.png" alt="QR Code Pix para doação" width="250">
</p>

🖼️ Conversor de Imagem ↔️ Base64 - Delphi

Este projeto é uma aplicação simples em **Delphi VCL** que permite converter imagens (JPEG/PNG) para texto Base64 e vice-versa. É útil para aplicações que necessitam armazenar ou transmitir imagens em formato textual.

## 🔄 Funcionalidades

- 📤 Carregamento de imagem local (JPEG ou PNG);
- 🔁 Conversão de imagem para string Base64;
- 📥 Conversão de Base64 de volta para imagem;
- 🧹 Limpeza da imagem e do texto Base64;
- 📋 Interface gráfica simples e intuitiva com campos de visualização e edição.

## 🧠 Como Funciona

- A imagem é carregada por meio de um `TOpenDialog` e exibida em um componente `TImage`;
- A conversão da imagem para Base64 é feita com a função `BitmapToBase64`;
- A conversão reversa é feita com a função `Base64ToBitmap`;
- As funções estão localizadas na unit auxiliar `untBase64Utils`.

## 🖼️ Interface

A interface consiste em:

- Campo para seleção do caminho da imagem;
- Botão para localizar a imagem no disco;
- Visualização da imagem carregada;
- Campo `TMemo` para visualização/edição do texto Base64;
- Botões para converter, reverter e limpar os dados.

## ▶️ Como Executar

1. Abra o projeto no **Delphi (RAD Studio)**;
2. Compile e execute o formulário `TfrmPrincipal`;
3. Clique em "Localizar Foto" e escolha uma imagem JPEG ou PNG;
4. Use os botões para converter a imagem para Base64 ou o texto de volta para imagem;
5. O campo `TMemo` será preenchido ou lido conforme a operação.

## 🔧 Requisitos

- Delphi (VCL);
- Suporte nativo a imagens PNG e JPEG;
- Unit `untBase64Utils` com funções de conversão.

## 📃 Licença

Este projeto está licenciado sob a MIT License.

---

Desenvolvido por Janderson Silva.
