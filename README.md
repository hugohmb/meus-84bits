# Meus 84Bits - Carrossel Interativo de Consoles Retrô

![Captura de tela do projeto Meus 84Bits]([Captura%20de%20tela%202025-06-09%20103334.jpg](https://github.com/hugohmb/meus-84bits/blob/main/Captura%20de%20tela%202025-06-09%20103334.png)

## 🚀 Sobre o Projeto

O "Meus 84Bits" é um projeto de site dinâmico e interativo que apresenta um carrossel de consoles de videogame retrô. Cada item do carrossel exibe uma imagem do console, seu nome e uma descrição detalhada, além de um botão "Open" que direciona o usuário para mais informações externas sobre o console. A navegação entre os consoles é feita através de setas laterais e indicadores visuais na parte inferior, tudo acompanhado de animações suaves para uma experiência de usuário envolvente.

Este projeto foi uma **evolução significativa** de uma videoaula inicial, sendo totalmente adaptado e aprimorado para um tema de consoles retrô e para incluir diversas otimizações e funcionalidades não presentes no original.

## ✨ Destaques e Evoluções

Embora inspirado em um projeto de carrossel, o "Meus 84Bits" foi redesenhado e refatorado extensivamente para se adequar ao tema de videogames retrô, com foco em:

* **Tema Personalizado:** Transição de um site automotivo para um universo de consoles de 8 e 16 bits, com imagens e textos totalmente novos e focados no nicho.
* **Design Único:** Adaptação da paleta de cores e tipografia para refletir a estética retrô, com gradientes e sombras que realçam os elementos visuais.
* **Melhoria da Interatividade:**
    * **Animações de Entrada:** Elementos como o título, descrição e botão "Open" agora possuem animações de entrada (`transform` e `opacity`) que se ajustam à direção da navegação (próximo ou anterior), criando uma transição mais fluida e intuitiva.
    * **Botão "Open" Otimizado:** Resolução de problemas de área clicável e eventos de `hover` para o botão de informações, garantindo uma interação precisa e responsiva em todas as áreas da página.
* **Estrutura CSS Refatorada:** Reorganização e ajuste de posicionamentos (`absolute`, `flexbox`), `z-index`, e tamanhos para garantir que os elementos do carrossel (imagem do console, título, descrição, botão) se comportem conforme o esperado, especialmente nas interações de clique e hover.
* **Responsividade Robusta:** Implementação de um arquivo CSS dedicado (`responsivo.css`) com múltiplas media queries para garantir que o layout se adapte perfeitamente a uma ampla gama de tamanhos de tela, desde monitores ultra-wide até smartphones, oferecendo uma experiência consistente e agradável em qualquer dispositivo.
* **Vanilla JavaScript:** Toda a lógica de navegação do carrossel e controle de estados (`active`) é implementada usando JavaScript puro, sem a necessidade de bibliotecas ou frameworks externos, demonstrando um controle fundamental sobre o DOM e eventos.

## 🛠️ Tecnologias Utilizadas

* **HTML5:** Estruturação semântica do conteúdo da página.
* **CSS3:** Estilização completa, incluindo layouts avançados (Grid, Flexbox), gradientes, sombras, transições e animações. Utilização de **Typekit** para fontes personalizadas.
* **JavaScript (Vanilla JS):** Implementação da lógica do carrossel, controle de slides, atualização de indicadores e gerenciamento das animações de entrada.

## ⚙️ Como Rodar o Projeto Localmente

Para visualizar e testar o projeto em sua máquina local:

1.  **Clone o Repositório:**
    ```bash
    git clone [https://github.com/SeuUsuario/SeuRepositorio.git](https://github.com/SeuUsuario/SeuRepositorio.git) # Substitua pelo seu link
    ```
2.  **Navegue até o Diretório:**
    ```bash
    cd NomeDoSeuRepositorio
    ```
3.  **Abra o Arquivo:**
    Simplesmente abra o arquivo `index.html` em seu navegador web preferido.

## 👨‍💻 Contribuição

Contribuições são bem-vindas! Se você tiver sugestões, melhorias ou quiser corrigir um bug, sinta-se à vontade para:

1.  Fazer um **fork** do projeto.
2.  Criar uma nova **branch** (`git checkout -b feature/minha-feature`).
3.  Fazer suas **alterações** e commitar (`git commit -m 'feat: minha nova feature'`).
4.  Fazer **push** para a branch (`git push origin feature/minha-feature`).
5.  Abrir um **Pull Request**.

## 🙏 Agradecimentos

Este projeto foi inspirado em uma videoaula sobre a criação de um carrossel interativo, no canal DevClub | Programação. A base conceitual e inicial do carrossel foram aprimoradas e adaptadas para criar uma experiência única e um design totalmente novo.

---

**Desenvolvido por Hugo Mendes Barbosa**
