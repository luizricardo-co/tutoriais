
# Gerando certificado apple
### Primeiro vc precisa gerar um CertificateSigningRequest.certSigningRequest
   - Vá na aplicação "Acesso a chave" no macbook
   - clique em: Acesso às chaves -> Assistente do certificado -> Solicitar um certificado de uma autoridade de certificação
    - Informe o email e nome comum e selecione salvar no disco.
 
 Registrando o CertificateSigningRequest.certSigningRequest no developer
 
 - entre em https://developer.apple.com/account
 - Certificates, Identifiers & Profiles
 - clique em (+)
 - selecione apple development ou apple distribution(caso queira publicar o app)
 - continue
 - selecione o arquivo CertificateSigningRequest.certSigningRequest no seu computador
 - continuar
 - faça o download e der dois cliques para instalar
 - pronto

# Gerando profiles
  - entre em https://developer.apple.com/account
  - vá em profiles
  - clique em (+)
  - selecione iOS app Development para desenvolvimento ou apple store para distribuição
  - continuar
  - selecione o identifier do projeto
  - continuar
  - selecione o certificado correspondente do seu macbook
  - continuar
  - selecione os devices que serão usados (Deve ter pelo menos 1)
  - continuar
  - insira o nome para o seu profile
  - continuar
  - Faça o download e der dois cliques para instalar
  - entre no xcode do seu projeto 
  - desmarque a opção de geração automatica
  - importe seu novo profile Gerado
  - pronto

# Gerando o .p12
  - Vá na aplicação "Acesso a chave" no macbook
  - clique em login
  - selecione a aba "Meus Certificados"
  - expanda o certificado desejado
  - clique com o botão direito na chave interna do certificado selecionado
  - clique em exportar "o nome do seu certificado"
  - selecione onde quer salvar
  - pronto
