# Valida Notícia

## Descrição
A ideia do projeto é fornecer um link que pode ser anexado a qualquer link de notícia, para além de exibi-la, verificar se a mesma é verdadeira ou não. 

Para a verificação da notícia, usamos os seguintes passos:

### 1. Verificação da Fonte
A primeira e mais importante parte do algoritmo é validar a fonte. Se ela vier de algum site reconhecidamente confiável, é dada automaticamente como verdadeira.

### 2. Perfis Verificados
Jornalistas de veículos conhecidos podem solicitar um perfil no **Valida Notícia** para indicar se as notícias são verdadeiras ou falsas, sendo comunicado através de email ou whatsapp.

### 3. Presença em sites confiáveis
Caso o site onde a notícia foi publicada não seja reconhecido como confiável, iremos buscar na internet se algum dos sites confiáveis também publicou a notícia. Caso positivo, a notícia será dada como confiável automaticamente.

### 4. Ortografia
Caso nenhuma das questões anteriores tenham sido verificadas, iremos analisar o texto para procurar por erros de ortografia. Geralmente as fake news possuem muitas palavras em caixa alta, adjetivos e erros ortográficos. Levaremos essa informação em consideração, mas ela não é suficiente sozinha para tornar uma notícia confiável, embora seja suficiente para tornar a notícia não-confiável.

### 5. Comunidade
Qualquer pessoa pode validar ou invalidar uma notícia através de voto, desde que devidamente identificada. Quanto mais verificações coerentes com a comunidade um usuário fizer, mais relevante será a sua participação no algoritmo de validação. 

*Os dois últimos itens são menos relevantes que os três primeiros. Eles são levado em considerações para dar suporte a veículos independentes que também podem ter furos, mas aí será necessária uma base de verificadores relevante para validar a notícia. Desta forma, os canais tradicionais são sim, sempre favorecidos quanto a confiança do conteúdo.*

## Layout Sugerido:
### 1. Notícia verdadeira:
### 2. Notícia verdadeira com detalhes:
### 3. Notícia falsa:
### 4. Notícia falsa com detalhes:
