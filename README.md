# ¿Este email es de fiar?

Detector de phishing gratuito. Pega un email sospechoso y en segundos te dice si tiene pinta de estafa, y por qué.

👉 **Pruébalo aquí:** [mlduque.github.io/es-de-fiar](https://mlduque.github.io/es-de-fiar/)

## ¿Para qué sirve?

Cada día recibimos correos que dicen venir de nuestro banco, de una empresa de mensajería o de una tienda online, y no siempre es fácil saber si son reales. Esta herramienta revisa el email por ti y te explica, en lenguaje sencillo, qué señales de estafa ha encontrado y qué deberías hacer.

## Cómo se usa

1. Copia el email sospechoso (si puedes, incluye la línea del remitente).
2. Pégalo en la herramienta y pulsa **Analizar email**.
3. Recibirás un veredicto (**Peligroso**, **Sospechoso** o **Sin alertas**), un nivel de riesgo de 0 a 100 y la explicación de cada señal encontrada.

Si quieres un análisis más preciso, usa la pestaña **Cabeceras**. En la propia web tienes una guía para copiarlas desde Gmail, Outlook, Apple Mail y Yahoo.

## Qué revisa

**El remitente**
- Si el nombre dice ser una empresa conocida pero la dirección no es suya.
- Si escribe desde una cuenta gratuita (Gmail, Hotmail…) haciéndose pasar por una empresa.
- Si las respuestas irían a una dirección distinta de la del remitente.

**Los enlaces**
- Webs que imitan a marcas conocidas, incluso cambiando letras por números (por ejemplo, *paypa1*).
- Enlaces acortados, direcciones numéricas (IP) y terminaciones muy usadas en estafas.
- Enlaces cuyo texto muestra una web pero llevan a otra.
- Enlaces sin conexión segura.

**El mensaje**
- Prisa o amenazas («su cuenta será bloqueada en 24 horas»).
- Peticiones de contraseñas, códigos o datos de tarjeta.
- Premios, reembolsos o pagos pendientes.
- El clásico timo del paquete retenido.
- Saludos genéricos y adjuntos peligrosos.

**La autenticación (modo cabeceras)**
- **SPF:** si el servidor que envió el correo está autorizado por el dominio.
- **DKIM:** si el mensaje tiene una firma digital válida y no se ha modificado.
- **DMARC:** si el dominio del remitente respalda el envío. Es la comprobación más fiable contra la suplantación.

## Tu privacidad

El email **no sale de tu dispositivo**. Todo el análisis se hace en tu navegador: no hay servidor, no se envía nada a ningún sitio y no se guarda nada.

## Si el resultado es «Peligroso» o «Sospechoso»

- No hagas clic en los enlaces ni descargues adjuntos.
- Si dice ser de una empresa, entra en su web o app escribiendo tú la dirección, o llama a su teléfono oficial.
- Márcalo como phishing o spam en tu correo.
- Si ya escribiste una contraseña o datos de tarjeta, cámbiala cuanto antes y avisa a tu banco.

## Ten en cuenta

Es una herramienta orientativa: ningún detector es infalible. Un resultado «Sin alertas» no garantiza al 100 % que un email sea seguro. Ante cualquier petición de dinero o datos, confirma siempre por otra vía.

## Sobre la autora

Creado por **María Luisa Duque**, Email Deliverability Manager.

Trabajo cada día para que los emails legítimos lleguen a la bandeja de entrada, y con esta herramienta quiero ayudar a que cualquiera pueda reconocer los que no lo son.

[Conecta conmigo en LinkedIn](https://www.linkedin.com/in/marialuisaduque/)
