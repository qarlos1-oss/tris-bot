# TRIS BOT 🎰

Sistema de análisis estadístico para el **Tris Clásico 21:00 hrs** de la Lotería Nacional Mexicana.

## Modalidades cubiertas
- **Directa 3**: Últimas 3 cifras · Premio $500 por peso
- **Par Final**: Últimas 2 cifras · Premio $50 por peso

## Estrategias implementadas
1. **Dígitos Frescos** — El 65% de los Clásicos tienen en R4/R5 dígitos que NO aparecieron en los 4 sorteos previos del día
2. **Vencidos (Overdue)** — Par Finales con mayor ausencia estadística
3. **Día de semana** — Frecuencia histórica por día
4. **Caliente reciente** — Par Finales más frecuentes en 90 días

## Base de datos
- **3,069 sorteos Tris Clásico** (1996–2026)
- Fuente: CSV oficial Lotería Nacional

## Deploy en Vercel

1. Fork / clona este repositorio
2. Importa en [vercel.com](https://vercel.com)
3. Deploy automático — sitio listo en minutos

## Uso

1. Ingresa los resultados de los 4 sorteos del día (13:00, 15:00, 17:00, 19:00)
2. Presiona **Analizar y Generar Predicción**
3. El sistema calcula las mejores apuestas para el Clásico 21:00

⚠️ Solo fines de análisis estadístico. La lotería es azar. Juegue responsablemente.
