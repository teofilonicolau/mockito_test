# Projeto de Testes com Mockito

Este projeto é destinado ao aprendizado e desenvolvimento de testes unitários utilizando a biblioteca Mockito. Ele contém exemplos práticos de como utilizar Mockito para mockar dependências e verificar comportamentos em diferentes cenários de teste.

### Descrição das Classes

- **ApiDosCorreios**: Interface que representa uma API de consulta de dados de localização a partir de um CEP.
- **CadastrarPessoa**: Classe responsável pelo cadastro de pessoas, utilizando a API dos Correios para obter dados de localização.
- **Conta**: Classe que representa uma conta bancária.
- **DadosLocalizacao**: Classe que encapsula dados de localização, como estado, cidade, rua, etc.
- **Email**: Classe que representa um email.
- **EnviarMensagem**: Classe responsável por enviar mensagens.
- **Formato**: Enum ou classe utilitária que define diferentes formatos de dados.
- **GeradorDeNumeros**: Classe responsável por gerar números (potencialmente um número de conta ou outro identificador).
- **Mensagem**: Classe que representa uma mensagem.
- **Pessoa**: Classe que representa uma pessoa.
- **PlataformaDeEnvio**: Interface ou classe que representa uma plataforma de envio de mensagens.
- **ServicoEnvioEmail**: Classe responsável pelo serviço de envio de emails.

### Descrição dos Testes

- **CadastrarPessoaTeste**: Testes para a classe `CadastrarPessoa`, verificando diferentes cenários de cadastro de pessoas.
- **CadastrarPessoaTeste2**: Testes adicionais para `CadastrarPessoa` com cenários diferentes ou configurações de mock variadas.
- **ContaTeste**: Testes para a classe `Conta`, verificando operações bancárias.
- **EnviarMensagemTest**: Testes para a classe `EnviarMensagem`, verificando o envio de mensagens.
- **LisTest**: Testes não especificados detalhadamente, mas presumivelmente para funcionalidades listadas.
- **ServicoEnvioEmailTest**: Testes para `ServicoEnvioEmail`, verificando o comportamento do serviço de envio de emails.

## Repositório

O repositório do projeto pode ser encontrado em [GitHub](https://github.com/teofilonicolau/mockito_test).

### Clonando o Repositório

Para clonar o repositório, utilize o seguinte comando:

```bash
git clone https://github.com/teofilonicolau/mockito_test.git
