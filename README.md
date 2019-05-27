# Trabalho Cesar 19/1 - 2ª parte

Trabalho do Cesar (segunda parte) para a cadeira de ARQ1 (2019/1), contendo implementação do kernel em arquivo fonte .ced

A documentação completa do trabalho se encontra em (../Documentacao/Especificacao.pdf).

## Funções do Kernel

O kernel implementado consiste em realizar 7 funções:

- KBHIT - Retorna ao programa se uma tecla foi pressionada no teclado;
- GETCHAR - Espera uma entrada de teclado pelo usuário;
- PUTCHAR - Coloca um caracter no visor;
- PUTMSG - Coloca uma string no visor;
- GETTIME - Retorna em segundos o tempo desde a inicialização do kernel;
- GETCLOCK - Retorna ao programa o valor das horas, minutos e segundos;
- SETCLOCK - Valida e salva valores para horas, minutos e segundos;


## Uso e Compatibilidade
O kernel implementado nesta parte no trabalho é totalmente compatível com a aplicação desenvolvida na parte 1, disponível [aqui](https://github.com/gabrielluizcm/TrabalhoCesar1aParte_19_1).

Para utilização do kernel, deve se usar o mesmo procedimento  de carregamento usado na parte 1:
>- Carregar o kernel pela função "Carregar (Ctrl+C)"
>- Com o kernel carregado, usar a função "Carga Parcial (Ctrl+P)" usando os seguintes parâmetros:
>> - Endereço Inicial: 256
>> - Endereço Final: 32767
>> - Endereço de Destino: 256

Após, o programa está pronto para ser executado devidamente.

### Aviso

Qualquer cópia do código, seja parcial ou total, é expressamente proibida, tendo em vista a anulação do trabalho para todas as partes caso constatado plágio.
