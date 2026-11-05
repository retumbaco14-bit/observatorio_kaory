# Observatorio de posicionamiento digital de Kaory en Loja

Observa la presencia en redes sociales de Kaory (calzado y moda de Zamora) frente a tiendas de calzado y moda de Loja. Proyecto integrador de Programación Aplicada a la Inteligencia de Mercados (UIDE Loja).

## Pregunta de negocio
¿Cómo se ubica el engagement de Kaory en Instagram y Facebook frente a cuatro tiendas de calzado y moda de Loja cada semana?

## Quién decide y qué decisión apoya
- **Quién decide:** Director de marketing digital de Kaory
- **Decisión:** Ajustar la frecuencia y el tipo de publicaciones (fotos, reels, promociones) y decidir en qué red invertir en publicidad pagada para atraer clientes de Loja.

## Indicadores
- Tasa de engagement semanal por marca (reacciones + comentarios + compartidos / seguidores × 100)
- Número de publicaciones por semana y por red social
- Crecimiento semanal de seguidores (%)

## Fuentes previstas
- Perfiles públicos de Instagram y Facebook de Kaory y de cada competidor
- Meta Business Suite de Kaory (estadísticas propias)
- Biblioteca de anuncios de Meta (publicidad activa de la competencia)

## Estructura del proyecto
- `data/raw/`: datos originales (no se modifican)
- `data/processed/`: datos limpios
- `notebooks/`: cuadernos de análisis
- `src/`: funciones reutilizables
- `reports/`: resultados para quien decide
- `pyproject.toml`: dependencias del proyecto

## Cómo ejecutar
Abrir el cuaderno en Google Colab y usar *Entorno de ejecución > Reiniciar sesión y ejecutar todo*.

## Declaración de uso de IA
Usé Claude (IA generativa) para redactar de mejor manera los campos del README enfocados en posicionamiento digital de Kaory

## Supuestos y limitaciones
- Supuesto: las interacciones visibles en los perfiles públicos (reacciones, comentarios y compartidos) reflejan el interés real del público de Loja.
- Supuesto: los seguidores de las tiendas competidoras son, en su mayoría, personas de Loja que podrían comprar en Kaory.
- Limitación: solo se observan Instagram y Facebook de cuatro tiendas de calzado y moda; no se ven TikTok, WhatsApp ni si las interacciones se convierten en ventas.

**Por qué importa:** con estos datos, el jefe de marketing digital de Kaory decidirá qué publicar, con qué frecuencia y en qué red invertir en publicidad para posicionarse en Loja.
