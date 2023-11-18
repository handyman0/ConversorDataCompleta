# Funções Diversas para Manipulação de Datas

Este script em Bash oferece diversas funções para manipular e formatar datas em diferentes formatos. Ele permite realizar as seguintes operações:

- **-f**: Retorna 0 para formato de data brasileiro (DDMMYYYY), 1 para formato americano (MMDDYYYY), 2 quando é impossível determinar e 3 para formato de data inválido.
- **-i**: Inverte o formato da data de brasileiro para americano e vice-versa, incluindo as barras.
- **-b**: Inclui barras na data, transformando-a de 13081981 para 13/08/1981, por exemplo.
- **-e**: Exibe a data em formato extenso, por exemplo, de 13081981 para 13 de Agosto de 1981.

## Uso

```bash
./FuncoesDiversas.sh --help
./FuncoesDiversas.sh OPÇÃO DATA
```

### Opções

- **-f**: Retorna o formato da data (0 para BR, 1 para US, 2 quando impossível determinar, 3 para inválido).
- **-i**: Inverte o formato da data.
- **-b**: Inclui barras na data.
- **-e**: Exibe a data em formato extenso.

### Exemplos

- Retornar o formato de uma data: `./FuncoesDiversas.sh -f 13081981`
- Inverter formato de data: `./FuncoesDiversas.sh -i 13081981`
- Incluir barras na data: `./FuncoesDiversas.sh -b 13081981`
- Exibir data em formato extenso: `./FuncoesDiversas.sh -e 13081981`

## Contribuindo

Contribuições são bem-vindas! Sinta-se à vontade para abrir uma *issue* ou enviar um *pull request*.

## Autor

Luiz Fernando

## Licença

Este projeto está licenciado sob a [Licença MIT](https://opensource.org/licenses/MIT).
```

Este é um exemplo simples que descreve as funcionalidades do script, seu uso e como contribuir. Lembre-se de adaptar conforme necessário e adicionar mais informações úteis sobre o projeto ou como executar o script.
