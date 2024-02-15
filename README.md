# Arduino-RGB-LED-Control

Este projeto demonstra como controlar um LED RGB com três potenciômetros usando uma placa Arduino. Os potenciômetros ajustam o brilho de cada cor do LED, e o monitor serial exibe a porcentagem de cada potenciômetro.

## Requisitos

- Placa Arduino (Uno, Nano, Mega, etc.)
- LED RGB de cátodo comum
- 3 potenciômetros de 10k ohms
- 3 resistores de 220 ohms
- Cabos jumper
- Protoboard

## Código

O código fonte do projeto está no arquivo `RGB_LED_Control.ino`. Ele usa as funções `analogRead()` para ler os valores dos potenciômetros, `map()` para converter os valores de 0 a 1023 para 0 a 255, `analogWrite()` para enviar os valores para os pinos do LED, e `Serial.print()` para imprimir os valores no monitor serial.

O LED RGB deve mudar de cor de acordo com os potenciômetros, e o monitor serial deve mostrar algo como:

```
Red: 50%
Green: 75%
Blue: 25%
```

## Imagens

![Esquemático do projeto](images/Aula_Pratica_1_schematics.jpg)

Esquema do projeto.

![Imagem do projeto](images/Aula_Pratica_1.png)

Imagem do projeto montado em uma protoboard.

## Licença

Este projeto está licenciado sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.