#  QA Mobile: Urban.Lunch

Pruebas manuales de la aplicación móvil **Urban.Lunch**, enfocadas en flujos principales de pedidos, UI y validaciones funcionales.

---

## 🔧 Herramientas utilizadas
<p align="center">
  <img src="https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white"/>
  <img src="https://img.shields.io/badge/Android%20Emulator-3DDC84?style=for-the-badge&logo=android&logoColor=white"/>
  <img src="https://img.shields.io/badge/Manual%20Testing-FF6F00?style=for-the-badge&logo=testing-library&logoColor=white"/>
</p>

---

## 📊 Resultados
- ✔️ **50 pruebas PASSED**  
- ❌ **4 pruebas FAILED**  

### 🐞 Defectos clave:
- **UL-3**: Textos largos en nombre de restaurante no se adaptan.  
- **UL-4**: El total no incluye costo de entrega.  
- **UL-5**: No se muestra tiempo de preparación por restaurante.  
- **UL-6**: Falta ETA de entrega en seguimiento.  

---

## 📄 Documentación completa
📌 [Ver documentación en Google Sheets](https://docs.google.com/spreadsheets/d/1WdPuxF7HGBQdSnRx216eLNqmWvRSKTtg/edit?usp=sharing&ouid=112657294087284506568&rtpof=true&sd=true)
---

## 🚀 Conclusión
El flujo principal de pedidos funciona de forma estable. Los defectos detectados afectan la **experiencia de usuario** en visualización y seguimiento, pero no bloquean el uso general de la aplicación.

## 🧾 Consideraciones adicionales en pruebas móviles
- ✅ Validación en **Android e iOS** con diferentes resoluciones y tamaños de pantalla.  
- ✅ Pruebas con **sensores**: giroscopio, acelerómetro, brillo y geolocalización.  
- ✅ Validación de **interrupciones**: llamadas entrantes, notificaciones, bloqueo de pantalla y batería baja.  
- ✅ Pruebas con distintos tipos de **red**: Wi-Fi, 3G, LTE y modo avión.  
- ✅ Revisión de **rendimiento**: tiempo de carga, consumo de batería y estabilidad.  
- ✅ Pruebas de **actualización**: instalación sobre versiones previas, arranque posterior y persistencia de datos de usuario.  

