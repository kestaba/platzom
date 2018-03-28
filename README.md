# Platzom

Platzom es un idioma inventado para el Curso de Fundamentos de JavaScript de [Platzi](https://platzi.com).

## Descripción del idioma

- Si la palabra original es un palindromo, ninguna regla anterior cuenta y se devuelve la misma palabra intercalando mayuscula uy minuscula

- Si la palabra termina en "ar", se le quitan esos dos caracteres

- Si la palabra inicia con Z, se le añade "pe" al final

- Si la palabra traducida tiene 10 o más letras, se debe partir a la mitad y unir con un guión medio

## Instalación

```
npm install platzom
```

## Uso

```
import platzom from 'platzom'

platzom("programar") //program
platzom("zorro") //zorrope
platzom("zarpar") //zarppe
platzom("abecedario") //abece-dario
platzom("sometemos") //SoMeTeMoS
```

## Créditos

- Platzi

## Licencia

[MIT](https://opensource.org/licenses/MIT)