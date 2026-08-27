# Super Tortas Vicky — Plan de digitalización

## Contexto del negocio
Lonchería local en Santiago Ixcuintla, Nayarit. Vende tortas,
hamburguesas, burritos, sincronizadas, papas, chocomilk y bebidas.
Cuenta con 3 locales: uno principal y 2 sucursales más pequeñas
con menú variable. Tiene muchos clientes, pero cero presencia
digital — no aparece en Google Maps, no tiene sitio web, y el
WhatsApp del negocio no está siendo atendido.

## Objetivo inmediato (demo para mañana)
Mostrar al dueño una demo funcional ya hosteada que demuestre
el valor del paquete. Debe verse como una inversión, no un lujo.

## FASE 1 — Paquete básico (entrega hoy, MX$2000)
Lo que se entrega y muestra en el demo:
- Landing page mobile-first con menú, sucursales, horarios,
  botón de WhatsApp
- Registro en Google Maps de los 3 locales con fotos y horarios
- WhatsApp Business configurado con respuestas automáticas 323 105 0023
  (bienvenida, menú rápido, mensaje fuera de horario)
- Google Sheets compartido entre los 3 locales para ver pedidos
- Código QR impreso para pegar en la entrada de cada local

## FASE 2 — Dashboard web (2-3 semanas después, MX$4,000-6,000)
Panel privado accesible desde tablet (Samsung Galaxy Tab A9+)
o cualquier navegador:
- Login para dueños
- Ver pedidos entrantes en tiempo real
- Cambiar estado de pedidos (recibido, en preparación, listo)
- Activar/desactivar atención automática por WhatsApp
- Estadísticas básicas (pedidos por día, hora pico, platillo más pedido)

## FASE 3 — Automatización avanzada (futuro)
- Bot de WhatsApp que toma pedidos automáticamente sin intervención
- Bot de llamadas telefónicas
- App móvil para repartidores

## Stack técnico
- Frontend: HTML/CSS/JS (Fase 1), luego Vue.js o Angular (Fase 2)
- Backend: Laravel + PostgreSQL (Fase 2)
- WhatsApp: WhatsApp Business API o Meta Cloud API
- Maps: Google Maps API + Google Business Profile
- Hosting: GitHub Pages (Fase 1), VPS o Railway (Fase 2)

## Recursos disponibles
- Demo ya desarrollada (index.html) — mejorable
- Imágenes reales del local disponibles
- QR code generado apuntando a la demo
- 2 tablets Samsung Galaxy Tab A9+ 5G disponibles para dashboard