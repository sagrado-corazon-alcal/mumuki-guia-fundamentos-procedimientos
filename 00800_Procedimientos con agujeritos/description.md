¿Y si ahora quiero hacer un cuadrado rojo? ¿O uno verde? ¿Tengo que escribir todo esto de vuelta? 

¡Por supuesto que **no**! ¡La programación se trata de automatizar tareas repetitivas! :smile:

Empecemos con algo fácil: supongamos que queremos **generalizar** el procedimiento `Poner3Verdes`, para que funcione con cualquier color que queramos (pero uno solo por vez). Lo que necesitamos es agregarle al procedimiento una especie de _agujero_...

```gobstones
procedure Poner3(color) {
  Poner(color)
  Poner(color)
  Poner(color)
}
```

...que luego pueda ser completado cada vez que se use: 

```gobstones
program {
  Poner3(Negro)
  Poner3(Rojo)
}
```

> Escribí los códigos anteriores en el editor y fijate qué pasa. 

