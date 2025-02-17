# Kendrick Data
Um projeto de análise de dados usando a API do Spotify para extrair e analisar informações sobre artistas e suas músicas.

## 🎯 Objetivo
O projeto visa criar uma análise abrangente de artistas no Spotify, explorando diferentes aspectos de suas músicas, álbuns e características técnicas, com foco inicial no artista Kendrick Lamar.

## 📋 Funcionalidades Implementadas

### Configuração Básica
- [x] Conexão com a API do Spotify
- [x] Configuração de credenciais no código
- [x] Funções de utilidade para extração de dados

### Análises Básicas (Primeiro Notebook)
- [x] Identificação da música mais popular
- [x] Música mais popular por álbum
- [x] Identificação do álbum mais popular
- [x] Duração das músicas
- [x] Artistas relacionados e suas músicas populares
- [x] Visualização da popularidade dos álbuns
- [x] Distribuição da popularidade das músicas


## Funcionalidades a Implementar

### Análises Adicionais
 - [ ]  Evolução temporal das características musicais
- [ ] Matriz de correlação entre características
- [] Análise de duração por álbum
- [ ] Análise de "mood" (humor) das músicas
- [ ] Características técnicas por álbum
- [ ] Rankings específicos (dançantes, energéticas)
- [ ] Análise de complexidade musical
- [ ] Estatísticas detalhadas das features
- [ ] Tendências temporais na popularidade


### Machine Learning
- [ ] Clustering de músicas por características
- [ ] Recomendação de músicas similares
- [ ] Análise de sentimento das letras
- [ ] Previsão de tendências musicais

## 🛠️ Tecnologias Utilizadas
- Python
- Spotipy (Biblioteca Python para Spotify API)
- Pandas
- Matplotlib
- Seaborn
- NumPy

## 📦 Dependências
```bash
pip install spotipy pandas matplotlib seaborn numpy
```

## 🚀 Como Usar
1. Clone o repositório
2. Instale as dependências
3. Configure suas credenciais do Spotify:
   ```python
   CLIENT_ID = 'seu_client_id'
   CLIENT_SECRET = 'seu_client_secret'
   ```
4. Execute os notebooks na ordem:
   - `spotify_basic_analysis.ipynb`
   - `spotify_advanced_analysis.ipynb`

## 📊 Exemplos de Análises
- Evolução temporal das características musicais
- Correlação entre diferentes aspectos das músicas
- Distribuição de popularidade por álbum
- Análise de complexidade musical vs. popularidade

## 📝 Notas
- A API do Spotify tem limites de requisição
- Algumas análises podem demorar devido ao volume de dados
- As credenciais devem ser mantidas em segurança
- Os resultados podem variar com o tempo devido à natureza dinâmica dos dados do Spotify

## 📄 Licença
Este projeto está sob a licença MIT.
