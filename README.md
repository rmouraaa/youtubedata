
# YouTube Video Statistics Fetcher

## Descrição

O **YouTube Video Statistics Fetcher** é um script em Python que utiliza a YouTube Data API para buscar e exibir estatísticas detalhadas de vídeos do YouTube. É particularmente útil para analisar tendências e a popularidade de conteúdos relacionados a uma palavra-chave específica no YouTube. Atualmente, o script está configurado para buscar vídeos relacionados a 'PicPay'.

## Funcionalidades

- Busca de vídeos no YouTube com base em palavras-chave.
- Ordenação de vídeos por contagem de visualizações.
- Filtragem de vídeos publicados no último ano.
- Recuperação de estatísticas detalhadas, incluindo visualizações, curtidas, descurtidas, comentários e tags.
- Exibição de miniaturas de vídeos.

## Instalação

Para instalar e executar este projeto localmente, siga os passos abaixo:

1. Clone o repositório:
    ```bash
    git clone https://github.com/seu-usuario/youtubedata.git
    cd youtubedata
    ```

2. Instale as dependências listadas no arquivo `requirements.txt`:
    ```bash
    pip install -r requirements.txt
    ```

## Uso

1. Obtenha uma chave de API do Google Cloud Console para acessar a YouTube Data API.
2. Substitua `'YOUR_API_KEY_HERE'` no script pela sua chave de API.
3. Execute o script para ver os resultados no console:
    ```bash
    python youtubedata.py
    ```

## Dependências

- `google-api-python-client`
- `datetime`

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para fazer um fork do repositório, fazer mudanças e enviar um pull request.

## Licença

Este projeto está sob uma licença livre. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.
