
# :brain: ZENITRAM

**Cyberdeck DIY – Proyecto Personal**


![DIY Project](https://img.shields.io/badge/type-DIY-blueviolet?style=flat-square&logo=wrench)
![Raspberry Pi](https://img.shields.io/badge/board-Raspberry%20Pi-red?style=flat-square&logo=raspberry-pi)
![Cyberpunk Inspired](https://img.shields.io/badge/inspired_by-Cyberpunk-ff69b4?style=flat-square&logo=circle)
![Portable](https://img.shields.io/badge/form_factor-Portable-brightgreen?style=flat-square&logo=battery-charging)
![Ultrawide Display](https://img.shields.io/badge/display-1280x400-informational?style=flat-square&logo=windowsterminal)
![r/cyberDeck](https://img.shields.io/badge/subreddit-r%2FcyberDeck-orange?style=flat-square&logo=reddit)

Bienvenido a **ZENITRAM**, mi proyecto personal para construir un **cyberdeck DIY** desde cero. No se trata solo de ensamblar piezas, sino de diseñar un dispositivo portátil que combine funcionalidad, identidad visual y un guiño nostálgico a la era del *cyberpunk* y la informática clásica.

**ZENITRAM** nace de la pasión por la estética retro-futurista, el amor por los proyectos *maker*, y el deseo de tener una máquina que no solo sea útil, sino que también cuente una historia. Inspirado por dispositivos como el **Penkesu Computer**, y por máquinas legendarias de los años 80 como el **Sharp PC-5000** o el **Tandy 200**, este proyecto es tanto un homenaje como una reinvención.

Mi objetivo es que **ZENITRAM** no sea simplemente "otro ciberterminal", sino una herramienta de trabajo y experimentación con alma: con un diseño único, pensado para ser compacto, autónomo y versátil; ideal para tareas como desarrollo ligero, terminal, scripting o incluso simplemente escribir sin distracciones.

---

## :mag: ¿Qué es un Cyberdeck?

El término **cyberdeck** proviene del universo **cyberpunk**, especialmente de la novela *Neuromancer* de **William Gibson** (1984), una obra fundacional del género. En ese mundo distópico, los *netrunners* (hackers del futuro) se conectan al ciberespacio mediante unos terminales portátiles llamados cyberdecks. Estos dispositivos les permiten navegar, infiltrarse en sistemas y manipular datos desde cualquier lugar, convirtiéndolos en una extensión física de su mente digital.

La imagen del cyberdeck se consolidó como un ícono de la cultura hacker futurista: terminales personales, compactos, potentes, llenos de teclas, luces, puertos y personalidad.

Décadas más tarde, ese concepto ha sido recuperado por la comunidad *maker*, reinterpretado y llevado a la práctica en forma de **ordenadores portátiles personalizados**, construidos con mini-PCs como la Raspberry Pi, teclados mecánicos personalizados, pantallas ultrapanorámicas y diseños únicos, a menudo impresos en 3D.

Hoy en día, un **cyberdeck real** no es solo una herramienta funcional. Es una **declaración estética**, una exploración técnica, una pieza de arte funcional. Es una forma de decir: *esto lo he hecho yo, a mi manera*.


---

## :dart: Objetivo del Proyecto

Mi intención es crear un **cyberdeck compacto y funcional**, que pueda utilizar para desarrollo ligero, terminales, dashboards personalizados, escritura o simplemente como objeto de diseño y autoaprendizaje.

Este repositorio servirá como:

  - Diario del proceso de construcción.
  - Registro de piezas y componentes (con enlaces a Amazon, AliExpress, etc.).
  - Referencias a otros proyectos que me han inspirado.
  - Código fuente, scripts y configuraciones que use para que el sistema funcione como quiero.

---

## :globe_with_meridians: Comunidad y Referencias

  - [Penkesu Computer](https://penkesu.computer/)
  - [r/cyberDeck en Reddit](https://www.reddit.com/r/cyberDeck/) – comunidad muy activa de proyectos similares
  - [Penk Chen (autor del Penkesu)](https://github.com/penk/penkesu)
  - [Awesome Cyberdecks](https://github.com/jakehilborn/awesome-cyberdecks) – recopilación de proyectos DIY

---

## :hammer_and_wrench: Inspiración Principal: Penkesu Computer

Una gran fuente de inspiración para este proyecto ha sido el **[Penkesu Computer](https://penkesu.computer/)**, un cyberdeck creado por [Penk Chen](https://github.com/penk/penkesu), que destaca por su:

  - Diseño plegable y portátil.
  - Uso de Raspberry Pi Zero 2 W.
  - Pantalla ultrapanorámica de 1280x400.
  - Teclado ortolineal con switches Choc v1.

![Penkesu](https://github.com/penk/penkesu/raw/master/gallery/penkesu.computer-heroshot.jpg)


Más [info](https://penkesu.computer/)

---

## :vhs: Herencia Retro: Sharp PC-5000 y Tandy 200

El diseño del Penkesu, y en parte el de mi proyecto, toma clara inspiración de portátiles clásicos como:

  - **[Sharp PC-5000](https://en.wikipedia.org/wiki/Sharp_PC-5000)** (1983)  
    ![Sharp PC-5000](https://upload.wikimedia.org/wikipedia/commons/6/66/Sharp_PC-5000_open.jpg)
    --SHARP PC 5000__
    
  - **[Tandy 200](https://en.wikipedia.org/wiki/Tandy_200)** (1984)  
    ![Tandy 200](https://en.wikipedia.org/wiki/File:Tandy_Model_200_(1).jpg)  
    __Tandy Model 200__

Estos dispositivos tenían forma de cuaderno, pantalla alargada y teclado físico completo, anticipando muchos aspectos de los portátiles modernos pero con una estética muy marcada que hoy consideramos retrofuturista.

---

## :package: Componentes del Proyecto

A continuación, una lista preliminar de los componentes necesarios para montar mi cyberdeck (versión inspirada en Penkesu):

### :brain: Computadora Principal

  - [Raspberry Pi Zero 2 W](https://www.raspberrypi.com/products/raspberry-pi-zero-2-w/)  
    Alternativas: Pi 4, CM4, o mini PCs como [LattePanda](https://www.lattepanda.com/), [Khadas VIM](https://www.khadas.com/)

### :desktop_computer: Pantalla

  - [Pantalla IPS 7.9” 1280x400 (Waveshare)](https://www.waveshare.com/7.9inch-hdmi-lcd.htm)  
    Compra en: [Amazon](https://www.amazon.es/dp/B09TBD8T8B) / [AliExpress](https://www.aliexpress.com/item/1005004420820463.html)

### :keyboard: Teclado Mecánico

  - [PCB personalizado para Choc v1](https://github.com/sekigon-gonnoc/PenkesuKeyboard)
  - [Switches Kailh Choc v1](https://www.kailh.com/en/Products/Ks/)
  - [Keycaps low profile para Choc](https://splitkb.com/collections/keycaps)

### :battery: Energía

  - [Batería LiPo 3.7V 2000–5000mAh](https://www.adafruit.com/category/574)
  - [Cargador/PowerBoost 5V USB con protección](https://www.adafruit.com/product/259)

### :control_knobs: Controlador de Teclado

  - [Nice!Nano](https://nicekeyboards.com/nice-nano/)  
    Alternativas: [Pro Micro + Bluetooth BLE Shield](https://www.sparkfun.com/products/retired/10915)

### :wrench: Otros

  - Bisagras tipo cuaderno (impresas o metálicas)
  - Tornillos, separadores, cables JST y jumpers
  - Carcasa impresa en 3D (próximamente en `/case`)
  - Interruptor físico, botón de encendido
  - LEDs RGB decorativos o indicadores

---

## :speech_balloon: ¿Por qué este proyecto?

Porque me encanta la estética **retro-futurista**, la filosofía **DIY** y la idea de tener un dispositivo que combine lo físico con lo digital, lo retro con lo moderno. Un **terminal personal hecho a mano**, que no solo funcione, sino que también cuente una historia.

---

## :books: Enlaces y recursos

Aquí iré recopilando enlaces a:

  - Componentes utilizados.
  - Otros proyectos que me inspiran.
  - Documentación técnica de teclado, pantalla, Pi, etc.
  - Herramientas para diseño 3D, impresión, configuración de Linux.

Todo estará organizado en carpetas como:

```

/docs
/components
/case
/software

```

---

## :construction: Estado del proyecto

Este proyecto está en curso. En esta primera fase me encuentro:

- Investigando componentes.
- Diseñando el chasis y el sistema.
- Tomando decisiones sobre el sistema operativo, flujo de trabajo, teclado, etc.

Puedes seguir los avances en la sección de Issues, Pull Requests y commits. También iré subiendo fotos y bocetos a medida que vaya avanzando.

---

## :camera: Galería

(En el futuro aquí incluiré imágenes del proceso y del cyberdeck finalizado.)

---

## :scroll: Licencia

Este repositorio está bajo licencia [MIT](LICENSE).

---

## :handshake: Colaboración

¿Tienes ideas o sugerencias? ¿Has construido uno y quieres compartir consejos? ¡Abre un issue o escríbeme!

---
