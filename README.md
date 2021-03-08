# TP1 usando a funcionalidade de Static Website de um Storage Account

Meu web site publicado no Azure consome apenas um *storage account* por meio de uma configuração disponível no Azure (Site Estático). Meu site é apenas um HTML contendo informações sobre definições de nuvem com exemplos de serviços e produtos. Você pode acessá-lo [clicando aqui](https://tp1modeloreferencia.z19.web.core.windows.net/)

**Abaixo um pequeno passo-a-passo de como criar um site estático com um storage account no azure:**

1. Crie um storage account
2. Habilite o site estático na opção "Configurar"
3. Informe a página inicial que a raiz do container $web irá apontar
4. Pronto! Você tem um site que pode ser hospedado no Azure opção de camada gratuita.

``
``

+ O site pode ser acessado de duas maneiras:
  - https://tp1modeloreferencia.z19.web.core.windows.net
  - https://tp1modeloreferencia.blob.core.windows.net/$web/index.html

