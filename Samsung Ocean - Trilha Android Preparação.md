# Samsung Ocean - Trilha Android: Preparação

A configuração do Android Studio pode ser feita com apenas alguns cliques.

Primeiro, verifique se você [fez o download da versão mais recente do Android Studio](https://developer.android.com/studio?hl=pt-br).

## Windows

Para instalar o Android Studio no Windows, faça o seguinte:

1. Se você fez o download de um arquivo `.exe`(recomendado), clique nele duas vezes para iniciá-lo.

   Se você fez o download de um arquivo `.zip`, descompacte o ZIP, copie a pasta **android-studio** para a pasta **Arquivos de Programas**, abra a pasta **android-studio > bin** e execute `studio64.exe` (para máquinas de 64 bits) ou `studio.exe` (para máquinas de 32 bits).

2. Siga as etapas do assistente de configuração no Android Studio e instale todos os pacotes do SDK **recomendados**.

### Vídeo

O vídeo a seguir mostra cada etapa do procedimento de configuração ao usar o download do `.exe` recomendado.

https://developer.android.com/studio/videos/studio-install-windows.mp4

## Mac

Para instalar o Android Studio no Mac, faça o seguinte:

1. Execute o arquivo DMG do Android Studio.
2. Arraste e solte o Android Studio na pasta Aplicativos e depois execute-o.
3. Selecione se você quer ou não importar as configurações anteriores do Android Studio e clique em **OK**.
4. O assistente de configuração do Android Studio orientará você durante o restante do processo, o que inclui o download dos componentes do SDK do Android que são necessários para o desenvolvimento.

O vídeo a seguir mostra todas as etapas do procedimento de configuração recomendado.

https://developer.android.com/studio/videos/studio-install-mac.mp4?hl=pt-br

O Android Studio informará a disponibilidade de novas ferramentas e outras APIs por uma janela pop-up. Além disso, você pode conferir se há atualizações clicando em **Android Studio > Check for Updates**.

> **Observação:** se você usa o Android Studio no macOS Mojave ou em uma versão mais recente, talvez receba uma solicitação para permitir que o ambiente de desenvolvimento integrado acesse sua agenda, seus contatos ou suas fotos. Essa solicitação é gerada por novos mecanismos de proteção de privacidade para aplicativos que acessam arquivos no diretório principal. Portanto, se o projeto incluir arquivos e bibliotecas no diretório principal e você receber essa solicitação, selecione **Não permitir**.

## Linux

Para instalar o Android Studio no Linux, faça o seguinte:

1. Descompacte o arquivo `.zip` transferido por download em um local apropriado para seus aplicativos, como `/usr/local/` para seu perfil de usuário ou`/opt/` para usuários compartilhados.

   Se você estiver usando uma versão de 64 bits do Linux, primeiro instale as [bibliotecas necessárias para máquinas de 64 bits](https://developer.android.com/studio/install?hl=pt-br#64bit-libs).

2. Para iniciar o Android Studio, abra um terminal, navegue até o diretório `android-studio/bin/` e execute `studio.sh`.

3. Selecione se você quer ou não importar as configurações anteriores do Android Studio e clique em **OK**.

4. O assistente de configuração do Android Studio orientará você durante o restante do processo, o que inclui o download dos componentes do SDK do Android que são necessários para o desenvolvimento.

> **Dica:** para disponibilizar o Android Studio na sua lista de aplicativos, selecione **Tools > Create Desktop Entry** na barra de menus do Android Studio.

### Bibliotecas necessárias para máquinas de 64 bits 

Se você estiver executando uma versão do Ubuntu de 64 bits, será necessário instalar algumas bibliotecas de 32 bits com o seguinte comando:

```bash
sudo apt-get install libc6:i386 libncurses5:i386 libstdc++6:i386 lib32z1 libbz2-1.0:i386
```

Se você estiver executando o Fedora de 64 bits, o comando será:

```bash
sudo yum install zlib.i686 ncurses-libs.i686 bzip2-libs.i686
```

### Vídeo

O vídeo a seguir mostra todas as etapas do procedimento de configuração recomendado.

https://developer.android.com/studio/videos/studio-install-linux.mp4?hl=pt-br

O Android Studio informará a disponibilidade de novas ferramentas e outras APIs por uma janela pop-up. Além disso, você pode conferir se há atualizações clicando em **Help > Check for Update**.

## Chrome OS

Siga estas etapas para instalar o Android Studio no Chrome OS:

1. [Instale o Linux para Chrome OS](https://support.google.com/chromebook/answer/9145439?hl=pt-br), se ainda não tiver feito isso.

2. Abra o app **Arquivos** e localize o pacote DEB na pasta **Downloads**, em **Meus arquivos**.

3. Com o botão direito do mouse, clique no pacote DEB e selecione **Instalar com o Linux (Beta)**.

   ![O local do arquivo de destino para o pacote DEB no Chrome OS.](https://developer.android.com/studio/images/studio-install-chromeos.png?hl=pt-br)

   - Se você já instalou o Android Studio antes, selecione se quer importar as configurações anteriores dele e clique em **OK**.

4. O **assistente de configuração** do Android Studio orientará você durante o restante do processo, o que inclui o download dos componentes do SDK do Android que são necessários para o desenvolvimento.

5. Após a conclusão da instalação, inicie o Android Studio pelo acesso rápido ou pelo terminal do Chrome OS Linux executando `studio.sh` no diretório de instalação padrão:

   `/opt/android-studio/bin/studio.sh`

O Android Studio informará a disponibilidade de novas ferramentas e outras APIs por uma janela pop-up. Além disso, você pode conferir se há atualizações clicando em **Help > Check for Update**.