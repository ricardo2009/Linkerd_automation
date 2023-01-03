<h1>Instalação e configuração do Linkerd em um cluster AKS</h1>

<p>Este script bash automatiza o processo de instalação, criação de chaves e configuração do Linkerd em um cluster AKS.</p>

<h2>Pré-requisitos</h2>

<ul>
  <li><a href="https://docs.microsoft.com/en-us/cli/azure/install-azure-cli">Azure CLI</a></li>
  <li><a href="https://kubernetes.io/docs/tasks/tools/install-kubectl/">kubectl</a></li>
</ul>

<h2>Uso</h2>

<ol>
  <li>Faça o clone do repositório: https://github.com/ricardo2009/Linkerd_automation
  
    git clone git@github.com:ricardo2009/Linkerd_automation.git && cd seu-repositorio
  
<li>Dê permissão de execução ao script:

    chmod +x linkerd_install.sh

<li>Execute o script:

    ./linkerd_install.sh

      
 Siga as instruções na tela para escolher as opções de instalação e criação de chaves. O script configurará o Linkerd automaticamente.

