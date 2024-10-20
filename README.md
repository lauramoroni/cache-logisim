# Simulação de Memória Cache no Logisim
Este repositório contém um projeto desenvolvido no Logisim, que simula o funcionamento de uma memória cache, realizado para fins didáticos.

## Estrutura do Projeto
O projeto é composto por um circuito que simula uma cache básica, composta pelos seguintes componentes:

- *Cache-line:* Representam as linhas da cache, contendo tags, dados e bits de validade.
- *Cache:* Responsável por gerenciar as operações de leitura e escrita na cache, verificando _hits_ ou _misses_.
- *Testbench:* Fornece uma sequência de acessos a memória, que devem ser inicializadas respectivamente com os arquivo `data.mem`, `address.mem` e `we.mem`.

## Funcionalidades
- Simulalçao de acertos e falhas
- Implementação de mapeamento conjunto associativo _4-way_

## Carregando memória de instruções
Para testar seu processador, os seguintes arquivos são fornecidos:

- [data.mem](https://github.com/lauramoroni/cache-logisim/blob/main/data.mem)
- [address.mem](https://github.com/lauramoroni/cache-logisim/blob/main/address.mem)
- [we.mem](https://github.com/lauramoroni/cache-logisim/blob/main/we.mem)

Para usar esses arquivos, é necessário clicar com o botão direito do mouse na **Memória RAM** no circuito `Testbench`, e **carregar os arquivos** com extensão `.mem`.
