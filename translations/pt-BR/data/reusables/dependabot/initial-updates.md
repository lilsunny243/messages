Quando você habilitar atualizações de versão pela primeira vez, você pode ter muitas dependências que estão desatualizadas e algumas podem ser muitas versões por trás da versão mais recente. O {% data variables.product.prodname_dependabot %} verifica as dependências desatualizadas assim que estiver habilitado. Você pode ver novas pull requests para atualizações de versão dentro de alguns minutos após adicionar o arquivo de configuração, dependendo do número de arquivos de manifesto para os quais você configura as atualizações.

Para manter os pull requests gerenciáveis e fáceis de revisar, o {% data variables.product.prodname_dependabot_short %} gera um máximo de cinco pull requests para começar a criar dependências até a versão mais recente. Se você fizer o merge de algumas destas primeiras pull requests antes da próxima atualização programada, então as próximas pull requests serão abertas até um máximo de cinco (você pode alterar esse limite).