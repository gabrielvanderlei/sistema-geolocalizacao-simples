# Sistema de Geolocalização Simples

## Definição

Esse sistema permite:
- Instanciar um mapa
- Conseguir a localização do usuário
- Conectá-lo a um banco de dados
- Permitir a visualização dos dados do banco
- Transformar esse sistema em um aplicativo simples

## Acerca de linguagens Web

O projeto é totalmente desenvolvido com linguagens Web. As linguagens Web são aquelas que formam toda a estrutura dos dados que trafegam pelo 
navegador, o protocolo HTTP - aquele utilizado para acessar os sites, significa HyperText Transfer Protocol (HTTP). Ele apenas realiza transmissão 
de hipertexto (um conjunto de dados que podem conter texto ou mídias), esse texto é codificado com HTML (HyperText Markup Language - Linguagem 
de marcação de hipertexto).

Essa linguagem se baseia na formatação por tags, uma tag é formada inicialmente por um < (menor que) e é finalizada por um > (maior que).
Todo elemento na linguagem é formado por uma tag de início e de fechamento, a tag de início pode conter propriedades, definidas pelo nome da 
propriedade seguido por um = (igual) e o valor da propriedade em seguida com aspas.

Exemplo: 
<b>Texto</b>

Retorna:
*Texto*

(b de bold, negrito em inglês)

O CSS e o JavaScript formam linguagens adicionais para estilizar e tornar os elementos do HTML mais dinâmicos. O CSS (Cascading StyleSheets) 
permite o desenvolvimento de estilos e o JavaScript é a linguagem de programação da Web e permite modificar as propriedades dos elementos HTML.

## Instanciando mapas

Para instanciar um mapa, podemos utilizar alguma das tecnologias de mapeamento abaixo:
- Google Maps
- Mapbox
- Here Maps
- ArgGIS Online

## Geolocalização

Para conseguir a localização do usuário vamos utilizar a tecnologia de geolocalização do navegador.
Navigator Geolocation API.

Ao contrário da API de geolocalização do celular, no desktop ela não é tão precisa.

## O banco de dados

Para conectar o sistema ao banco de dados vamos utilizar o Firebase.
O Firebase é um sistema que permite não apenas o armazenamento de dados (local e em tempo real), mas o envio de notificações, a criação de sistemas de login e registro, 
armazenamento de arquivos, processamento de dados, machine learning, entre outras tecnologias.

Para o projeto em questão, vamos utilizar o armazenamento de dados em tempo real, de um modo bem simples. Para uso em produção é necessário 
realizar ajustes nas regras do banco de dados, que controla a segurança dos dados no Firebase.

Todo sistema de mapas possui uma abordagem para adicionar pontos. Esses pontos em geral precisam de uma imagem e de um conjunto de coordenadas, 
atravez de um padrão denominado GeoJSON. O GeoJSON utiliza a estrutura de dados JSON para representar elementos geográficos.

## Transformando em aplicativo

Para transformar o site em aplicativo vamos utilizar a plataforma Phonegap Build. Recomendo estudar a tecnologia Java com o Android Studio, para 
criação de apliativos nativos prontos para produção, ou procurar mais informações sobre o framework React Native.

