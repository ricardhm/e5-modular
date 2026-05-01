# e5 — Modelo de Negocio Completo
### Estrategia · Pricing · Pipeline · Operación · Estructura Fiscal CR 2026

---

## Índice

1. [Estructura Fiscal y Proyecciones Financieras](#1-estructura-fiscal-y-proyecciones-financieras)
2. [Flujo de Caja — Año 1 Mes a Mes](#2-flujo-de-caja--año-1-mes-a-mes)
3. [Arquitectura de Pricing](#3-arquitectura-de-pricing)
4. [Modelo de Pipeline Comercial](#4-modelo-de-pipeline-comercial)
5. [Proceso de Propuesta](#5-proceso-de-propuesta)
6. [Templates — Las 3 Conversaciones](#6-templates--las-3-conversaciones)
7. [Onboarding del Primer Cliente](#7-onboarding-del-primer-cliente)
8. [Estructura Interna de Operación](#8-estructura-interna-de-operación)
9. [Modelo de Contractors](#9-modelo-de-contractors)
10. [Estrategia de Contenido LinkedIn](#10-estrategia-de-contenido-linkedin)

---

## 1. Estructura Fiscal y Proyecciones Financieras

### Principio rector

La carga fiscal real en Costa Rica 2026 determina el revenue requerido para llegar a las metas de take-home. La estructura correcta es una **S.A. con distribución vía dividendos**, bajo el régimen del Decreto 45333-H (escala reducida PYME).

### Mecánica fiscal completa

| Capa | Tasa | Aplica sobre |
|---|---|---|
| Impuesto corporativo (PYME) | Escala reducida ~18.3% efectiva | Renta Neta ≤ ¢119.17M |
| Impuesto corporativo (general) | 30% flat | Renta Neta > ¢119.17M |
| Retención de dividendos | 15% | Utilidades distribuidas |
| IVA | 13% | Pass-through; el cliente lo paga, no afecta Renta Neta |

**Tipo de cambio:** ¢515/USD  
**Tasa efectiva total Año 1:** 30.5% (PYME)  
**Tasa efectiva total Años 2–3:** 40.5% (30% corporativo)

---

### El cliff del régimen PYME — riesgo crítico

> **Umbral 2026: ¢119.17M de Renta Neta ≈ $231k ex-IVA ≈ $261k facturación incl. IVA**

Cruzar este umbral por ¢1 activa el 30% sobre **toda** la Renta Neta. La penalidad súbita equivale a ≈$29,700 USD.

**¿Por qué el Escenario B "teórico PYME" no aplica en la práctica?**

El umbral aplica sobre Renta Bruta. Cualquier gasto deducible obliga a generar más ingresos para mantener la misma Renta Neta, y esos ingresos adicionales cruzan el umbral. Los gastos mínimos de operación de una firma lean de 2 personas:

| Gasto | Monto estimado |
|---|---|
| Software y herramientas (Notion, Claude, Zoom, etc.) | ¢1.5M |
| Contabilidad + asesoría legal | ¢4.0M |
| Comunicación, seguros, misceláneos | ¢2.0M |
| **Total estimado** | **¢7.5–11M** |

Con estos gastos, cualquier nivel de revenue que apunte a $75k por socio **cruza el umbral con certeza**. Planificar Año 2 con tarifa PYME es construir sobre un supuesto que no aguanta la operación mínima real.

---

### IVA 13% — mecánica real

- **Es neutro para la empresa:** se cobra al cliente, se acredita el IVA pagado en compras, y se remite el saldo neto a Hacienda mensualmente.
- **No entra en el cálculo de Renta Neta** ni afecta la utilidad.
- **Efecto práctico:** el cliente paga ×1.13 sobre la tarifa acordada.
- **Regla de trabajo:** siempre calcular con valores ex-IVA internamente. La factura al cliente incluye el +13% de forma explícita.
- **Para clientes corporativos:** el IVA pagado es acreditable para ellos. El costo real para su empresa es el ex-IVA.

---

### Tabla maestra — desglose fiscal por escenario

| Rubro | **Año 1 (A)** | **Año 2 (B-real)** | **Año 3 (C)** |
|---|---|---|---|
| **Take-home neto por socio** | **$50,000** | **$75,000** | **$100,000** |
| Take-home combinado | $100,000 | $150,000 | $200,000 |
| Régimen fiscal | PYME ✅ | 30% 🔴 | 30% 🔴 |
| Tasa efectiva corporativa | ~18.3% | 30.0% | 30.0% |
| Tasa efectiva total (corp. + div.) | 30.5% | 40.5% | 40.5% |
| Impuesto corporativo | $26,500 | $75,600 | $100,800 |
| Retención dividendos (15%) | $17,600 | $26,500 | $35,300 |
| OPEX estimado | $12,500 | $28,000 | $48,000 |
| **Revenue ex-IVA requerido** | **$157,000** | **$280,000** | **$384,000** |
| **Facturación clientes (incl. IVA)** | **$177,000** | **$317,000** | **$434,000** |
| Crecimiento YoY | — | +79% | +37% |

---

### Mix de revenue por año — ex-IVA (base imponible empresa)

| Tipo | Año 1 ($157k) | Año 2 ($280k) | Año 3 ($384k) |
|---|---|---|---|
| Diagnósticos | 2 × $11k = $22k | 3 × $13k = $39k | 4 × $14k = $56k |
| Core engagements | 3 × $40k = $120k | 4 × $48k = $192k | 5 × $55k = $275k |
| Retainers | $15k | $49k | $53k |

> **Para la cara del cliente:** multiplicar los valores ex-IVA × 1.13. Facturación total incl. IVA: $177k / $317k / $434k.

---

### Acción prioritaria — estructura legal

Contratar un contador con experiencia en firmas de servicios profesionales en Costa Rica **antes de facturar el primer cliente**. La diferencia entre una S.A. mal estructurada y una S.A. con optimización salario+dividendo puede ser $15–20k/año. En Q4 del Año 2, evaluar la estructura híbrida salario+dividendo para Año 3 (potencial ahorro de hasta $16k/año adicional).

---

## 2. Flujo de Caja — Año 1 Mes a Mes

### El problema estructural del consulting: el desfase

> **Pipeline hoy → propuesta en 3–4 semanas → cierre en 6–8 semanas → primer pago en semana 10–12.**

Lo que hagan en enero determina si cobran en marzo o abril. El flujo de caja en consulting vive 60–90 días adelante de la actividad comercial.

**Reserva recomendada antes de lanzar: $12,000 USD**

---

### Supuestos del modelo

| Supuesto | Valor |
|---|---|
| Estructura de pago proyectos | 50% al inicio / 25% mid / 25% al cierre |
| Diagnósticos | 100% al inicio |
| Retainers | Cobro mensual anticipado |
| Ciclo de venta promedio | 8 semanas desde primer contacto |
| OPEX mensual promedio | ~$1,040/mes |
| Impuesto corporativo | Provisionado 25% mensual; pagado en pagos parciales trimestrales (~$6,600 c/u en meses 3, 6, 9, 12) |
| Cifras | Ex-IVA (el IVA cobrado se remite mensualmente a Hacienda) |

---

### Flujo mes a mes — Año 1 (USD, ex-IVA)

| Mes | Actividad principal | Cash IN | Cash OUT | Saldo mes | Acumulado |
|---|---|---|---|---|---|
| **Enero** | Setup legal/contable, outreach intensivo | $0 | $3,500 | **-$3,500** | -$3,500 |
| **Febrero** | 2 propuestas enviadas | $0 | $1,500 | **-$1,500** | -$5,000 |
| **Marzo** | Cierra Diagnóstico #1 | $11,000 | $1,500 | **+$9,500** | +$4,500 |
| **Abril** | Cierra Core #1 (50% anticipo) | $22,000 | $2,000 | **+$20,000** | +$24,500 |
| **Mayo** | Ejecución Core #1 + outreach | $0 | $1,500 | **-$1,500** | +$23,000 |
| **Junio** | Core #1 final (50%) + Retainer #1 | $28,000 | $2,000 | **+$26,000** | +$49,000 |
| **Julio** | Diagnóstico #2 + Core #2 anticipo | $33,000 | $2,000 | **+$31,000** | +$80,000 |
| **Agosto** | Retainer activo + ejecución | $6,000 | $1,500 | **+$4,500** | +$84,500 |
| **Septiembre** | Core #2 final | $22,000 | $2,000 | **+$20,000** | +$104,500 |
| **Octubre** | Core #3 anticipo + Retainer | $28,000 | $2,000 | **+$26,000** | +$130,500 |
| **Noviembre** | Ejecución + outreach Año 2 | $6,000 | $1,500 | **+$4,500** | +$135,000 |
| **Diciembre** | Core #3 final + pago impuesto corp. | $22,000 | $28,500 | **-$6,500** | +$128,500 |
| **TOTAL** | | **$178k aprox.** | **$49.5k** | | **$128,500 bruto** |

---

### Destino del acumulado de $128,500

| Destino | Monto |
|---|---|
| Dividendos pre-retención (utilidad distribuible) | $117,600 |
| Retención de dividendos 15% → Hacienda | $17,600 |
| **Neto en mano por socio** | **$50,000 c/u ✅** |

---

### Las 4 fases del año

```
ENE–FEB        MAR–JUN         JUL–SEP          OCT–DIC
──────────────────────────────────────────────────────────
Inversión       Despegue        Velocidad         Cosecha
-$5k            +$49k           +$104.5k          +$128.5k
Setup + outreach Primer cierre  Motor activo      Año 2 en pipeline
```

---

### Los 3 momentos de riesgo crítico

| Riesgo | Cuándo | Mitigación |
|---|---|---|
| **Valle de los 60 días** | Ene–Feb | Tener $12k de reserva personal antes de lanzar |
| **Proyecto que se extiende** | Cualquier mes | Milestones contractuales con fechas, no solo entregables |
| **Pagos parciales de impuesto** | Meses 3, 6, 9, 12 | Provisionar 25% desde el primer cobro — cuenta separada, no tocar |

---

### Años 2 y 3 — vista anual actualizada

| | Año 2 | Año 3 |
|---|---|---|
| Facturación incl. IVA | $317k | $434k |
| Revenue ex-IVA | $280k | $384k |
| OPEX (incl. contractors) | $28k | $48k |
| Impuesto corporativo (30%) | $75,600 | $100,800 |
| Retención dividendos (15%) | $26,500 | $35,300 |
| **Take-home por socio** | **$75,000** | **$100,000** |
| Meses cash-negative | 0 | 0 |

> En Año 2, los retainers cubren el OPEX mensual base → los proyectos son puro upside.

---

## 3. Arquitectura de Pricing

### Principio rector: pricing basado en valor, no en tiempo

Venden **resultados a CXOs**, no horas de consultor. El precio se ancla en el valor que el cliente captura. Un CXO que toma una decisión estratégica correcta vale 10–100x el fee de consultoría.

**3 reglas de pricing que no se rompen:**
1. **Nunca cotizar por hora** — penaliza eficiencia y los posiciona como staff, no como advisors
2. **Siempre fixed-fee por fase** — protege margen si la metodología mejora; da certeza al cliente
3. **Anclar el precio al valor del cliente** — "$40k para mover una decisión de $5M es barato — díganlo explícitamente"

---

### Capa 1 — Entrada: Diagnóstico Estratégico

**Precio: $11,000–$15,000 ex-IVA | Cliente paga: $12,400–$17,000 incl. IVA**

| Elemento | Detalle |
|---|---|
| Qué es | Assessment ejecutivo de 3–4 semanas |
| Entregable | Documento ejecutivo + sesión de readout con C-suite |
| Horas reales | 40–60h entre ambos |
| Pago | 100% al inicio |
| Conversión a core | 60–70% |
| Función estratégica | Puerta de entrada — baja la barrera de entrada al pipeline |

---

### Capa 2 — Core: Engagement de Estrategia / Innovación

**El centro de gravedad del negocio. 70–80% del revenue.**

| Tipo de engagement | Precio ex-IVA | Cliente paga (incl. IVA) |
|---|---|---|
| Estrategia de una unidad / área | $38,000–$52,000 | $43,000–$59,000 |
| Innovación / nuevo modelo de negocio | $52,000–$68,000 | $59,000–$77,000 |
| Transformación organizacional / C-suite | $68,000–$85,000 | $77,000–$96,000 |

**Estructura de pago:** 50% al inicio / 25% al hito intermedio / 25% al cierre  
**Formato:** Fixed-fee por fase — nunca por hora  
**Duración típica:** 6–16 semanas

---

### Capa 3 — Retainer: Advisory Ejecutivo Continuo

**Precio: $5,500–$9,000/mes ex-IVA | Cliente paga: $6,200–$10,200/mes incl. IVA**

| Elemento | Detalle |
|---|---|
| Formato | 2–4 sesiones/mes + disponibilidad async |
| Compromiso mínimo | 3 meses (idealmente 6–12) |
| Pago | Mensual anticipado |
| Capacidad máxima | 4–5 retainers simultáneos sin sacrificar calidad |
| Función estratégica | Revenue predecible + relación de largo plazo |

> En Año 2, los retainers cubren el OPEX mensual completo → los proyectos son puro upside.

---

### Cómo presentar el precio en la conversación de ventas

**Nunca presentar el precio solo. Siempre en contexto de valor:**

```
❌ Malo:
"El costo del proyecto es $42,000 + IVA"

✓ Bueno:
"La inversión para este engagement es $42,000 + IVA (13% = $5,460 adicionales
en la factura). Dado que están evaluando [decisión de $X millones], esto
representa menos del Y% del valor en juego — y el IVA es recuperable
para su empresa como crédito fiscal."
```

**Con clientes que reaccionan al IVA:**
> "El 13% de IVA que pagan es acreditable en su declaración. Su costo neto real es el precio ex-IVA — el IVA no sale de su bolsillo en términos económicos."

---

## 4. Modelo de Pipeline Comercial

### La matemática del funnel — Año 1

**Meta: 7 cierres (4 core + 2 diagnósticos + 1 retainer)**

| Etapa | Conversión | Volumen requerido |
|---|---|---|
| Cierres necesarios | — | **7** |
| Propuestas enviadas | 40% → cierre | 18 propuestas |
| Reuniones exploratorias | 50% → propuesta | 36 reuniones |
| Contactos calificados | 40% → reunión | 90 contactos |
| **Universo total de outreach** | 15% → calificado | **~600 touchpoints** |

**600 touchpoints / 12 meses = 50 touchpoints/mes = ~12/semana.** Manejable para 2 personas si el proceso está sistematizado.

---

### Las 3 fuentes de pipeline

| Fuente | % del pipeline | Tasa de cierre | Esfuerzo |
|---|---|---|---|
| **Red existente (warm)** | 60% | 45–55% | Bajo |
| **Referidos de clientes** | 25% | 60–70% | Muy bajo |
| **Outreach frío / contenido** | 15% | 5–10% | Alto |

**Implicación directa:** los primeros 90 días deben ser casi exclusivamente activación de red. El outreach frío es un juego de Año 2, cuando ya hay casos de éxito.

---

### Actividad comercial semanal por socio (6–8 horas)

| Actividad | / semana | / mes |
|---|---|---|
| Mensajes de reactivación de red | 8 | 32 |
| Llamadas / cafés exploratorios | 2 | 8 |
| Follow-ups propuestas activas | 3 | 12 |
| Contenido publicado (LinkedIn) | 1 | 4 posts |
| Propuestas enviadas | ~0.5 | ~2 |

---

### Pipeline ponderado — probabilidades por etapa

| Etapa | Probabilidad |
|---|---|
| Contacto inicial | 10% |
| Reunión exploratoria | 25% |
| Propuesta enviada | 50% |
| Propuesta en negociación | 75% |
| Verbal yes | 90% |

**Fórmula:** Pipeline ponderado = Σ (valor oportunidad × % probabilidad de cierre)

**Meta mínima en todo momento: >$80k de pipeline ponderado.**  
**Señal de alerta: <$50k → acción inmediata.**  
**Reunión de revisión: viernes AM, 30 minutos.**

---

### El CRM mínimo viable — 5 columnas en Notion

| Campo | Para qué sirve |
|---|---|
| Contacto + empresa | Identidad |
| Etapa del funnel | Dónde está en el proceso |
| Valor estimado (ex-IVA) | Para calcular pipeline ponderado |
| **Próxima acción + fecha** | El más importante — sin esto muere el deal |
| Probabilidad % | Para monitorear pipeline ponderado |

---

### El error más común en consulting de 2 personas

> **Dejan de vender cuando están en delivery.**

El patrón típico: cierran un proyecto → se enfrascan 8 semanas en entregarlo → terminan → pipeline vacío → 2 meses sin revenue.

**La solución:** designar roles. Uno lidera delivery, el otro mantiene el ritmo comercial. Rotan por proyecto.

---

## 5. Proceso de Propuesta

### El principio rector

> Si la propuesta es la primera vez que el cliente ve el precio, ya perdieron.

**La propuesta confirma, no convence.** El trabajo de ventas ocurre antes del documento, en 3 conversaciones estructuradas. La propuesta solo formaliza lo que ya acordaron verbalmente.

```
Conversación 1    Conversación 2    Conversación 3    PROPUESTA
──────────────────────────────────────────────────────────────
Diagnóstico del   Alineación de     Pre-cierre de     Documento
dolor             solución          condiciones       formal

"¿Qué les está   "Esto es lo       "Si resolvemos    Envían el
costando esto?"   que haríamos"     esto, tiene       PDF/Notion
                                    sentido?"         doc
```

---

### Las 3 conversaciones — criterios de avance

#### Conversación 1 — Diagnóstico del dolor (45–60 min)

**Objetivo:** entender el problema real, no el síntoma que presentan.

| Bloque | Preguntas |
|---|---|
| **El problema** | "¿Qué está pasando específicamente?" · "¿Desde cuándo y por qué ahora?" · "¿Qué han intentado ya?" · "¿Cómo están midiendo el impacto?" |
| **Costo de no actuar** | "¿Qué pasa si no resuelven esto en 6 meses?" · "¿Cuánto les está costando en revenue, tiempo, oportunidad?" · "¿Es prioridad del C-suite o iniciativa del área?" |
| **La decisión** | "¿Quién más está involucrado?" · "¿Han trabajado con consultores antes?" · "¿En qué plazo querrían arrancar?" |

✅ **Criterio de avance:** conocen el problema, el costo aproximado, quién decide y hay urgencia real. Si falta alguno → investigar antes de agendar Conv. 2.

---

#### Conversación 2 — Alineación de solución (45 min)

**Objetivo:** co-construir el enfoque con el cliente, no presentarles uno.

| Tiempo | Bloque |
|---|---|
| 10 min | Recap de lo que escucharon → valida que entendieron bien |
| 20 min | "Así es como lo abordaríamos..." → presentan enfoque (máximo 1 página, nunca un deck completo) |
| 10 min | Preguntas de co-diseño → el cliente ajusta |
| 5 min | Cierre → agendar Conv. 3 |

**Preguntas de co-diseño:**
- "¿Qué le cambiarían a este enfoque?" ← nunca "¿qué les parece?"
- "¿Hay alguna restricción interna que debamos considerar?"
- "¿Esto resuelve lo que necesitan, o hay algo que no estamos viendo?"

✅ **Criterio de avance:** el cliente co-diseñó el enfoque y no tiene objeciones estructurales sin resolver. Si las hay → resolverlas aquí, no en el documento.

---

#### Conversación 3 — Pre-cierre de condiciones (20–30 min)

**Objetivo:** confirmar precio, timing y decisión antes de escribir una sola página. Siempre por llamada, nunca email.

**Las 3 validaciones en orden exacto:**

| Validación | Pregunta exacta | Señales |
|---|---|---|
| **Presupuesto** | "Proyectos de este alcance típicamente están en el rango de [$X–$Y ex-IVA], más IVA del 13%. ¿Eso está dentro de lo contemplado?" | Verde: sí · Amarillo: "está alto" → ajustar alcance, no precio · Rojo: "no tenemos presupuesto" → diagnóstico primero |
| **Timing** | "¿Cuándo necesitarían tener esto resuelto? ¿Y cuándo querrían arrancar?" | Brecha entre ambas = urgencia real |
| **Decisión** | "Asumiendo que la propuesta refleja lo hablado, ¿quién más necesita verla antes de avanzar?" | Solo él → propuesta directa · CFO/CEO → incluirlos en la revisión · Comité → saber cuándo se reúne |

✅ **Criterio de avance:** las 3 tienen respuesta clara y positiva. Si el presupuesto no existe o hay 4 niveles de aprobación desconocidos → replantear antes de invertir tiempo en el documento.

---

### El documento de propuesta — estructura exacta (6–8 páginas, nunca más de 10)

| # | Sección | Contenido | Páginas |
|---|---|---|---|
| 1 | **El contexto** | El problema en sus propias palabras | 1 |
| 2 | **Lo que está en juego** | Costo de no actuar, oportunidad de capturar | 1 |
| 3 | **Nuestro enfoque** | Fases (máximo 3), metodología, por qué este camino | 2 |
| 4 | **Lo que recibirán** | Entregables concretos por fase — no genéricos | 1 |
| 5 | **Cronograma** | Timeline visual, hitos, checkpoints | 1 |
| 6 | **Inversión** | Precio ex-IVA + nota "+13% IVA según ley", estructura de pagos, qué incluye y qué no | 1 |
| 7 | **Próximos pasos** | Exactamente qué pasa si dicen sí — sin ambigüedad | 0.5 |

---

### El protocolo post-envío — donde se gana o se pierde el 40%

| Momento | Acción | Por qué |
|---|---|---|
| **Mismo día del envío** | Mensaje: "Te la acabo de enviar — avísame cuando la hayas visto para agendar 20 min" | Crea compromiso de revisión |
| **48 horas después** | Llamada de revisión — nunca email | Las objeciones reales emergen en voz |
| **En la llamada** | "¿Qué preguntas tienen?" — no "¿qué les pareció?" | Orienta hacia cierre, no hacia opinión |
| **Si dicen "lo estamos evaluando"** | "¿Qué necesitarían ver para poder avanzar?" | Revela la objeción real |
| **Silencio +5 días** | Un solo follow-up: "Quiero asegurarme de que tienen todo lo que necesitan para decidir" | No perseguir — dar control |

---

### Las 3 objeciones más comunes

| Objeción | Lo que realmente significa | Respuesta correcta |
|---|---|---|
| "El precio está alto" | No ven claro el valor | "¿Qué parte del alcance ajustaríamos para que tenga sentido?" — **nunca bajar precio sin reducir alcance** |
| "Necesitamos pensarlo" | Hay un stakeholder no alineado | "¿Tiene sentido que hablemos juntos con [esa persona]?" |
| "No es el momento" | Urgencia insuficiente o presupuesto no existe | "¿Cuándo sería el momento? ¿Qué tendría que cambiar?" |

---

## 6. Templates — Las 3 Conversaciones

### Template Conversación 1 — Diagnóstico del dolor

**Apertura:**
```
"[Nombre], gracias por el tiempo. Antes de hablar de nosotros o de lo que
hacemos, quiero entender bien qué está pasando en [empresa].
¿Te parece si empezamos por ahí?"
```

**Bloque 1 — El problema:**
```
1. "Cuéntame qué está pasando con [tema]. ¿Qué les preocupa específicamente?"
2. "¿Desde cuándo está pasando esto, y por qué están abordándolo ahora?"
3. "¿Qué han intentado ya para resolverlo?"
4. "¿Cómo están midiendo el impacto de este problema hoy?"
```

**Bloque 2 — Costo de no actuar:**
```
5. "Si esto no se resuelve en los próximos 6 meses, ¿qué pasa?"
6. "¿Tienen una estimación de lo que esto les está costando —
   en revenue, tiempo, oportunidad?"
7. "¿Esto es prioritario para el C-suite o es una iniciativa del área?"
```

**Bloque 3 — La decisión:**
```
8. "¿Quién más está involucrado en resolver esto?"
9. "¿Han trabajado con consultores externos antes para algo similar?"
10. "Si encontraran el enfoque correcto, ¿en qué plazo querrían arrancar?"
```

**Cierre:**
```
"Lo que me cuentas tiene mucho sentido. Déjame procesar esto con mi socio
y preparar una perspectiva inicial de cómo lo abordaríamos.
¿Tiene sentido que agendemos 45 minutos la próxima semana
para compartirles esa visión?"
```

---

### Template Conversación 2 — Alineación de solución

**Apertura — el recap:**
```
"Antes de compartir nuestra perspectiva, quiero asegurarme de que entendí
bien lo que hablamos. Lo que escuché fue:

— El problema central es [X]
— El impacto que están viendo es [Y]
— La urgencia viene de [Z]

¿Lo estoy leyendo bien, o hay algo que deba ajustar?"
```

**Presentación del enfoque:**
```
"Dado lo que nos contaron, así es como lo abordaríamos:

FASE 1 — [Nombre] (semanas 1–X):
  → Qué haremos
  → Por qué primero esto
  → Qué tendrán al final de esta fase

FASE 2 — [Nombre] (semanas X–Y):
  → Qué haremos
  → Por qué este orden
  → Qué tendrán al final

FASE 3 — [Nombre] (semanas Y–Z):
  → Entregable final
  → Cómo se ve el éxito

Lo diseñamos así porque [razón específica basada en lo que dijeron]."
```

**Preguntas de co-diseño:**
```
"¿Qué le cambiarían a este enfoque?"
"¿Hay alguna restricción interna que debamos considerar?"
"¿Esto resuelve lo que necesitan, o hay algo que no estamos viendo?"
```

**Cierre:**
```
"Perfecto. Con estos ajustes, tiene sentido que preparemos una propuesta
formal. Antes de hacerlo, necesito alinear un par de cosas prácticas
contigo — ¿tienes 20 minutos esta semana para una llamada corta?"
```

---

### Template Conversación 3 — Pre-cierre de condiciones

**Apertura:**
```
"[Nombre], antes de armar la propuesta quiero asegurarme de que lo que
preparemos tenga sentido completo para ustedes. Son tres cosas rápidas."
```

**Validación 1 — Presupuesto:**
```
"Proyectos de este alcance, con este nivel de complejidad, típicamente
están en el rango de [$X–$Y ex-IVA], más IVA del 13% que aplicaría
en la factura. ¿Eso está dentro de lo que tienen contemplado
para esta iniciativa?"
```

**Respuestas y acciones:**
- "Sí, está bien" → confirmar y avanzar
- "Está un poco alto" → "¿En qué rango están pensando?" — ajustar alcance, nunca precio
- "No tenemos presupuesto" → "¿Cuándo lo tendrían? ¿O prefieren empezar con el diagnóstico?"

**Validación 2 — Timing:**
```
"¿Cuándo necesitarían tener esto resuelto?
Y en términos de cuándo arrancar, ¿hay alguna fecha que funcione
mejor internamente?"
```

**Validación 3 — La decisión:**
```
"Asumiendo que la propuesta refleja todo lo que hablamos, ¿quién más
necesita verla o estar involucrado antes de que puedan avanzar?"
```

**Cierre — proponer revisión conjunta en el mismo momento del envío:**
```
"Perfecto. Con esto claro, vamos a preparar la propuesta.
Te la enviamos el [día concreto — máximo 5 días hábiles].
Cuando la tengas, agendemos 20 minutos para revisarla juntos
— tiene más sentido que leerla solo."
```

---

## 7. Onboarding del Primer Cliente

### El principio rector

> El cliente no evalúa solo el entregable final. Evalúa **cómo se sintió el proceso completo** desde el día que firmó.

Los primeros 7 días son los más críticos. La mayoría de firmas desaparecen entre la firma y el kickoff. Ese silencio destruye confianza antes de empezar.

---

### Bloque 1 — Confirmación inmediata (Día 0: mismo día de la firma)

**Mensaje por WhatsApp o canal personal — mismo día:**
```
"[Nombre], bienvenido. Estamos genuinamente emocionados con este
proyecto. En las próximas 24 horas te enviamos la confirmación
formal y el plan para las primeras 2 semanas.
Cualquier cosa que necesites antes, aquí estamos."
```

**Dentro de las primeras 24 horas envían:**

| Documento | Contenido |
|---|---|
| Carta de bienvenida | Reconfirma el problema, el enfoque y lo que verán en semanas 1–2 |
| Plan de primeras 2 semanas | Fechas exactas, reuniones agendadas, qué necesitan de ellos |
| Lista de accesos/información | Concreta y priorizada — no 20 items de golpe |

---

### Bloque 2 — Kickoff meeting (Días 3–5)

**Duración:** 60–90 min | **Asisten:** Ambos socios + todos los stakeholders del cliente

| Tiempo | Bloque | Propósito |
|---|---|---|
| 10 min | Recap del contexto | Alinear a todos (no todos estuvieron en las conversaciones previas) |
| 15 min | El problema redefinido | Presentan su lectura — el cliente corrige o valida |
| 20 min | Plan de trabajo | Fases, hitos, entregables, fechas concretas |
| 15 min | Modelo de trabajo | Comunicación, frecuencia de reuniones, escalación de problemas |
| 10 min | Lo que necesitan del cliente | Accesos, tiempos, decisiones que dependen de ellos |
| 10 min | Preguntas | Resolver dudas antes de empezar |

**Al final del kickoff, el cliente debe saber exactamente:** qué va a pasar cada semana · quién hace qué · cómo y cuándo se comunican · qué necesitan de ellos y para cuándo.

---

### Bloque 3 — Cadencia semanal de trabajo

| Touchpoint | Frecuencia | Formato | Duración |
|---|---|---|---|
| Status update | Semanal | Email / Notion doc | 5 min de lectura |
| Reunión de trabajo | Semanal o quincenal | Video / presencial | 60 min |
| Check-in ejecutivo | Mensual | Con el CXO sponsor | 30 min |
| Revisión de hito | Por fase | Presentación formal | 90 min |

**Template del status update semanal (siempre la misma estructura):**
```
SEMANA [N] — [Nombre del proyecto]
─────────────────────────────────────

✅ COMPLETADO ESTA SEMANA
   — [Item 1]
   — [Item 2]

🔄 EN PROGRESO
   — [Item 1] → listo el [fecha]
   — [Item 2] → listo el [fecha]

📌 PRÓXIMA SEMANA
   — [Lo que harán]
   — [Lo que harán]

⚠️ NECESITAMOS DE SU LADO
   — [Acción específica] → para el [fecha]
   — [Decisión pendiente] → para el [fecha]

📊 ESTADO GENERAL: 🟢 En tiempo / 🟡 En riesgo / 🔴 Atrasado
```

> El status update tiene una función secundaria crítica: **documenta el progreso y protege a ambas partes** si hay disputas sobre alcance o avance.

---

### Bloque 4 — Expansión natural (Semana 3–4)

**Pregunta de expansión — cuando hay avance concreto que mostrar:**
```
"[Nombre], mientras trabajamos en esto hemos visto [observación relevante
sobre otra área]. No está dentro del alcance actual, pero creemos que
vale la pena que lo conversemos — podría ser importante para
[resultado que le importa al cliente]. ¿Tiene sentido que lo exploremos?"
```

**Los 3 momentos naturales de expansión:**

| Momento | Qué observar | Cómo plantear |
|---|---|---|
| Semana 3–4 | Problema adyacente que emerge | "Mientras trabajamos en X, vimos Y" |
| Entrega de hito | Área que necesitará seguimiento | "Para que esto funcione a largo plazo..." |
| Cierre del proyecto | Próxima iniciativa lógica | "El paso natural después de esto sería..." |

---

### Bloque 5 — Protocolo de cierre del proyecto

**La última semana del engagement:**

| Actividad | Propósito |
|---|---|
| Sesión de readout ejecutivo | Presentación formal del trabajo completo al C-suite |
| Documento de impacto | 1 página: problema → enfoque → resultados → próximos pasos |
| Retrospectiva interna | 30 min entre socios — qué funcionó, qué mejorar |
| Conversación de cierre con sponsor | 1:1 — cómo se sintió el proceso, qué valor capturaron |

**Pregunta de feedback en la conversación de cierre:**
```
"[Nombre], hay algo que nos importa mucho saber:
¿hubo algo que pudiéramos haber hecho diferente o mejor durante el proceso?"
```

**Pregunta del referido — si el engagement fue exitoso:**
```
"Nos alegra mucho que haya tenido este impacto.
¿Hay alguien en tu red — un colega, alguien de tu industria —
que esté enfrentando un desafío similar y a quien creas
que podríamos ayudar?"
```

---

## 8. Estructura Interna de Operación

### El principio rector: claridad sobre democracia

```
❌ "Decidimos todo juntos"  →  fricción, lentitud, resentimiento
✅ "Cada uno tiene dominios claros con ownership total"
```

---

### División de roles — ownership por dominio

| Dominio | Ric | Jose Luis | Decide |
|---|---|---|---|
| Estrategia comercial | Owner | Input | Ric |
| Desarrollo de negocio / pipeline | Owner | Soporte | Ric |
| Delivery de proyectos | Compartido | Compartido | Líder del proyecto |
| Metodología e IP | Input | Owner | Jose Luis |
| Finanzas y operación | Owner | Input | Ric |
| Contenido y posicionamiento | Compartido | Compartido | Acuerdo |
| Decisiones de hire / contractor | Acuerdo | Acuerdo | Ambos |

> **Líder por proyecto:** en cada engagement, uno es el lead — punto de contacto principal con el cliente, responsable del entregable. Se define antes del kickoff.

---

### Cadencia de reuniones internas

| Reunión | Frecuencia | Duración | Agenda |
|---|---|---|---|
| **Weekly sync** | Lunes AM | 45 min | Pipeline + proyectos activos + blockers + finanzas |
| **Pipeline review** | Viernes AM | 30 min | Oportunidades + próximas acciones + pipeline ponderado |
| **Retrospectiva mensual** | Último viernes del mes | 90 min | Qué funcionó + qué cambiar + decisiones Tipo C + salud de sociedad |
| **Planeación trimestral** | Primer lunes del trimestre | 3 horas | Revenue vs. meta + ajustes + prioridades |

**Agenda exacta del Weekly Sync (45 min):**
```
LUNES — WEEKLY SYNC
─────────────────────────────────────────
10 min  PIPELINE
        — Oportunidades nuevas esta semana
        — Propuestas activas y próximos pasos
        — Pipeline ponderado actual vs. meta ($80k mínimo)

20 min  PROYECTOS ACTIVOS
        — Estado por proyecto (🟢🟡🔴)
        — Blockers que necesitan resolverse
        — Qué necesita cada cliente esta semana

10 min  OPERACIÓN
        — Finanzas: facturas, cobros pendientes, provisión fiscal
        — Decisiones pendientes entre socios

5 min   PRIORIDAD #1 DE LA SEMANA
        — Cada uno dice su foco principal
```

---

### Modelo de toma de decisiones — 3 tipos

| Tipo | Definición | Ejemplos | Proceso |
|---|---|---|---|
| **Tipo A — Operativas** | Impacto reversible, bajo riesgo | Cómo estructurar un entregable, herramienta a usar | Owner del dominio decide solo |
| **Tipo B — Tácticas** | Impacto moderado, reversible | Precio de propuesta, alcance de proyecto | Consulta al otro socio, decide el owner |
| **Tipo C — Estratégicas** | Impacto alto o irreversible | Hire, pivot, cliente anchor, deuda | Acuerdo de ambos — no se mueve sin consenso |

**La regla de los 24 horas:** Decisión Tipo C sin acuerdo en Weekly Sync → 24h de reflexión individual → reunión específica de 30 min → decisión. Si no hay acuerdo → quien tiene el dominio, desempata.

---

### Stack de herramientas internas

| Necesidad | Herramienta | Qué va ahí |
|---|---|---|
| Pipeline y CRM | Notion | Oportunidades, etapa, valor, próxima acción |
| Gestión de proyectos | Notion | Plan de trabajo, entregables, status por cliente |
| Documentos internos | Notion | Templates, metodología, acuerdos entre socios |
| Comunicación diaria | WhatsApp | Operativo — no para decisiones importantes |
| Finanzas | Google Sheets | Revenue, facturas, cobros, provisión fiscal |
| Contratos y propuestas | Notion + PDF | Versionado y firmado digitalmente |

> **Regla de oro:** si no está en Notion, no existe. Todo acuerdo, decisión Tipo C y cambio de alcance con cliente queda documentado.

---

### Distribución de horas por socio / semana (45h)

| Actividad | Horas | % |
|---|---|---|
| Delivery (proyectos activos) | 25h | 55% |
| Desarrollo de negocio / ventas | 8h | 18% |
| Operación interna / admin | 4h | 9% |
| Desarrollo propio / metodología | 4h | 9% |
| Buffer / imprevistos | 4h | 9% |

**Regla del 70%:** Si el delivery supera el 70% de las horas disponibles de ambos socios simultáneamente → están en zona de riesgo. Activar un contractor antes de cerrar el siguiente proyecto.

**Techo práctico sin contractor:** 2 core engagements + 1 diagnóstico + 2 retainers.

---

### Acuerdos de sociedad — por escrito antes del primer cliente

| Acuerdo | Decisión a tomar |
|---|---|
| División de utilidades | 50/50 o diferenciado — definir desde el inicio |
| Salarios internos | ¿Se pagan salario base o solo distribuyen utilidades? |
| Horas de dedicación mínima | Expectativa explícita — evita resentimiento |
| Política de clientes propios | Si alguien trae cliente de su red, ¿cómo se contabiliza? |
| Cláusula de salida | Buy-out — incómodo hoy, crítico mañana |
| Deadlock en Tipo C | Si no hay acuerdo, ¿qué mecanismo usan? |

---

### Las 5 preguntas de salud de la sociedad — revisión mensual

Cada socio las responde por separado, de forma honesta, antes de la retrospectiva mensual:

```
1. ¿Siento que la carga de trabajo está distribuida equitativamente?
2. ¿Hay alguna decisión reciente con la que no estoy de acuerdo
   y no dije nada?
3. ¿Estoy haciendo trabajo que no me corresponde sin haberlo conversado?
4. ¿Hay algo que el otro socio hace (o no hace) que me está afectando?
5. ¿Estamos avanzando hacia donde acordamos ir?
```

> Si alguna respuesta es incómoda → entra a la retrospectiva como punto obligatorio. Las tensiones entre socios que no se nombran estallan en los momentos de mayor presión.

---

## 9. Modelo de Contractors

### El principio rector: contratan capacidad, no personas

```
❌ "Necesitamos ayuda → contratemos alguien"
✅ "Este proyecto necesita X horas de Y skill → activamos el contractor correcto"
```

---

### Señal de activación del primer contractor

Cualquiera de estas 3 condiciones:
1. El delivery de ambos socios supera el 70% por 2 semanas seguidas
2. Tienen una oportunidad de cierre que excede la capacidad actual
3. Un proyecto requiere un skill que ninguno de los dos tiene

**En el Año 1, el primer contractor aparece típicamente en el mes 6–8.**

---

### Los 3 perfiles — en orden de prioridad

#### Perfil 1 — Analyst / Consultor Junior (el más urgente)

| Elemento | Detalle |
|---|---|
| Qué hace | Research, decks, análisis de datos, documentación de entregables |
| Qué NO hace | Contacto directo con CXOs, diseño estratégico, ventas |
| Perfil ideal | 2–4 años, consultoría o estrategia, excelente comunicación escrita |
| Carga típica | 20–30h por proyecto |
| Tarifa mercado LATAM | $15–25/hora |
| Costo por proyecto | $3,000–$5,000 |
| Markup en fee al cliente | 40–50% |
| Impacto en margen | Reduce margen de ~87% a ~75%, pero libera 20–30h de socios para más ventas |

#### Perfil 2 — Especialista por dominio (Año 2)

| Especialidad | Cuándo | Tarifa estimada |
|---|---|---|
| Data / analytics | Proyectos con componente de datos | $40–60/hora |
| Diseño de experiencia / UX | Innovación con componente de usuario | $30–50/hora |
| Facilitación | Workshops con equipos grandes | $500–1,000/día |
| Legal / finanzas estratégico | Due diligence | $60–100/hora |

> **Markup 30–40%**. Presentar al cliente como "soporte especializado del equipo" — no revelar la estructura interna.

#### Perfil 3 — Project Coordinator (Año 2–3)

| Elemento | Detalle |
|---|---|
| Qué hace | Status updates, agendamiento, tracking, administrativo |
| Formato | Part-time 20h/semana, remoto |
| Tarifa mercado CR | $800–$1,200/mes |
| Impacto | Libera 8–10h/semana por socio de trabajo no estratégico |

---

### El modelo económico — el contractor nunca sale de su bolsillo

| Costo real | Cobrado al cliente | Markup |
|---|---|---|
| Analyst 25h × $20 = $500 | $700–$750 en el fee | 40–50% |
| Especialista 10h × $50 = $500 | $650–$700 en el fee | 30–40% |
| Coordinator $800/mes | Repartido entre proyectos activos | — |

---

### Protocolo de selección y activación

**Antes de necesitarlo (primeros 90 días de la firma):**
1. Identificar 3–5 candidatos por perfil en la red existente
2. Tener una conversación exploratoria con cada uno
3. Hacer un paid test ($100–$200) con los mejores
4. Definir: tarifa, disponibilidad típica, forma de trabajo
5. **Resultado:** bench de 2–3 contractors pre-validados que se activan en 48–72 horas

**Protocolo por proyecto:**

| Paso | Acción | Cuándo |
|---|---|---|
| Brief del proyecto | 1 página: contexto, entregables, timeline, tarifa | Día 1 |
| NDA | Acuerdo de confidencialidad — siempre, sin excepción | Día 1 |
| Kickoff del contractor | 30 min: expectativas, estándares, comunicación | Día 2 |
| Checkpoint semanal | 15 min: qué entregó, qué sigue, blockers | Semanal |
| Revisión de calidad | Todo entregable pasa por un socio antes de ir al cliente | Siempre |

---

### Las 3 reglas de calidad — no negociables

1. **Nada va al cliente sin revisión de un socio** — siempre
2. **El contractor no tiene contacto directo con el CXO** — todo contacto ejecutivo pasa por los socios
3. **Los estándares se documentan, no se asumen** — documento "así trabajamos" que todo contractor recibe

**Contenido del documento "así trabajamos":**
```
1. Estándares de presentación de entregables
2. Tono de comunicación escrita
3. Cómo estructuran un análisis
4. Qué nivel de detalle esperan
5. Cómo marcan versiones y cambios
6. Tiempos de respuesta esperados
7. Cómo escalan un problema
```

---

### Evolución del modelo

| | Año 1 | Año 2 | Año 3 |
|---|---|---|---|
| Estructura | Bench de 3 pre-validados | 1–2 analysts recurrentes | 2 analysts + 1 coordinator |
| Costo/año | $0 | $15–25k (~10% revenue) | $40–55k (~12–15% revenue) |
| Core simultáneos posibles | 2 | 4–5 | 7–8 |

---

## 10. Estrategia de Contenido LinkedIn

### El principio rector: no venden servicios — enseñan a pensar

```
❌ No funciona:   "Somos expertos en estrategia"
                  "Ayudamos a empresas a crecer"

✅ Funciona:      "Aquí está el error que cometen la mayoría de
                  CEOs al diseñar su estrategia"
                  "Por qué el 70% de las transformaciones fracasan"
```

> LinkedIn no es marketing — es el pipeline de ventas más barato. El CXO que los sigue porque aprende algo valioso ya los percibe como expertos antes de la primera conversación.

---

### Los 3 pilares de contenido

| Pilar | Propósito en el funnel | % del contenido |
|---|---|---|
| **Educación estratégica** | Posicionamiento y credibilidad | 50% |
| **Perspectiva y opinión** | Diferenciación y voz propia | 30% |
| **Prueba social y proceso** | Conversión y confianza | 20% |

---

### Pilar 1 — Educación estratégica

**Formatos:**
- **El framework** — herramienta mental para resolver un problema común (2x/mes)
- **El error común** — desmitificar una práctica extendida que no funciona (2x/mes)
- **El paso a paso** — cómo abordar una decisión estratégica específica (2x/mes)

**Ejemplo de post — El framework:**
```
Los CEOs que toman mejores decisiones estratégicas
no tienen más información.

Tienen mejores preguntas.

Estas son las 4 que usamos en todo engagement:

1. ¿Cuál es el costo real de no decidir?
2. ¿Estamos resolviendo el problema o el síntoma?
3. ¿Quién se beneficia de mantener el status quo?
4. ¿Qué tendría que ser verdad para que esto funcione?

La mayoría de organizaciones saltan directo a soluciones
sin responder estas preguntas.

El resultado: iniciativas costosas que no mueven la aguja.

¿Cuál de estas le cuesta más a tu organización responder?
```

---

### Pilar 2 — Perspectiva y opinión

**Formatos:**
- **La contra-opinión** — desafiar una idea establecida en su industria (2x/mes)
- **La observación de tendencia** — lo que están viendo antes de que sea obvio (1x/mes)
- **La lección aprendida** — algo que cambió en su forma de pensar (1x/mes)

**Ejemplo de post — La contra-opinión:**
```
Opinión impopular: la mayoría de consultoras están
incentivadas a que no resuelvas tu problema.

Sus modelos de negocio viven de proyectos largos,
equipos grandes y scope que se expande.

Nosotros construimos el modelo opuesto:

→ Proyectos acotados con entregables claros
→ Fee fijo — no por hora
→ Éxito medido en decisiones que tomaste,
   no en páginas que entregamos

No es altruismo. Es que creemos que así se construye
una firma que dura.

¿Cuándo fue la última vez que tu consultor te dijo
que no necesitabas lo que estabas comprando?
```

---

### Pilar 3 — Prueba social y proceso

**Formatos:**
- **El caso sin nombre** — "Un CEO en retail nos llamó con este problema..." (2x/mes)
- **Detrás del proceso** — metodología hecha visible (1x/mes)
- **La pregunta del cliente** — una pregunta real y su respuesta completa (1x/mes)

**Ejemplo de post — El caso sin nombre:**
```
Un CEO nos llamó hace 3 meses con esto:

"Llevamos 2 años hablando de transformación digital
y no hemos movido nada."

El problema no era tecnología.
No era presupuesto.
No era talento.

Era que nadie en el C-suite tenía el mismo problema en mente.

Lo primero que hicimos no fue un diagnóstico técnico.
Fue una sesión de 3 horas con el equipo ejecutivo
para responder una pregunta:

¿Qué problema estamos realmente resolviendo?

Esa claridad desbloqueó los siguientes 18 meses.

A veces el problema estratégico más caro
no es el que ven — es el que no han nombrado.
```

---

### Cadencia semanal — 4 posts entre ambos socios

| Día | Quién | Pilar | Formato |
|---|---|---|---|
| **Lunes** | Ric | Educación | Framework o paso a paso |
| **Miércoles** | Jose Luis | Opinión | Contra-opinión o tendencia |
| **Jueves** | Ric | Prueba social | Caso sin nombre o proceso |
| **Viernes** | Jose Luis | Educación | Error común o lección |

> Por qué no publican el mismo día: el algoritmo de LinkedIn favorece cuentas individuales sobre páginas empresa. Dos socios en días distintos duplica el alcance sin duplicar el esfuerzo.

---

### El sistema de producción — 90 minutos/semana por socio

| Momento | Tiempo | Acción |
|---|---|---|
| Domingo noche | 30 min | Revisar los 2 posts de la semana (del banco de ideas) |
| Lunes AM | 20 min | Pulir y programar el post del lunes |
| Miércoles PM | 20 min | Pulir y programar el post del jueves/viernes |
| **Total** | **~90 min** | |

**Fuentes para el banco de ideas (capturar en Notion en tiempo real):**
1. Conversaciones con clientes → "El CEO me dijo X — ahí hay un post"
2. Problemas que resuelven → "Esto que hicimos hoy merece explicarse"
3. Lecturas y tendencias → "Este artículo tiene una contra-opinión"
4. Preguntas que les hacen → "Si me lo preguntó uno, se lo preguntan 100"
5. Errores propios → "Esto lo hicimos mal — y lo que aprendimos"

> **Meta: banco de ideas con mínimo 20 temas en todo momento.** Cuando baja de 10 → sesión de 30 min de brainstorming conjunto.

---

### Templates de engagement — los más importantes

**DM post-engagement (cuando un CXO comenta algo sustantivo):**
```
"[Nombre], gracias por tu comentario — me parece que tocas algo
importante que no desarrollé en el post: [punto específico
que mencionaron].

¿Tienes 20 minutos para conversarlo?
Creo que hay algo interesante ahí."
```

**Solicitud de conexión (nunca genérica):**
```
"[Nombre], leí tu comentario sobre [tema específico] y me pareció
que tocas algo que pocas personas en [industria] están viendo bien.

Me gustaría tenerte en mi red."
```

---

### KPIs de contenido — qué medir y qué ignorar

**No medir:**
- Likes generales → vanity metric
- Seguidores totales → no pagan facturas
- Impresiones → alcance sin contexto

**Medir semanalmente:**

| Métrica | Meta Año 1 | Por qué importa |
|---|---|---|
| Comentarios de CXOs target | 3–5 por post | Indica que llegan al perfil correcto |
| DMs entrantes | 2–4 por semana | Demanda inbound generada |
| Reuniones desde LinkedIn | 2–3 por mes | Conversión directa a pipeline |
| Conexiones nuevas target (CXOs+VPs) | +50/mes | Expansión del universo relevante |

---

### Estrategia de crecimiento de red

| Prioridad | Perfil | Por qué |
|---|---|---|
| Alta | CEOs, CGOs, CDOs, CMOs de empresas $10M–$500M en LATAM | Cliente directo |
| Alta | Socios de VCs y PE con portfolio en LATAM | Referidores de alto volumen |
| Media | Directores de estrategia e innovación | Campeones internos |
| Media | Consultores complementarios | Referidos cruzados |
| Baja | Recruiters, vendedores, peers junior | Ruido |

---

### Timeline realista de resultados

| Periodo | Estado | Leads inbound |
|---|---|---|
| Mes 1–2 | Setup + consistencia | 0 |
| Mes 3–4 | Primeros comentarios de CXOs | 1–2 conversaciones |
| Mes 5–6 | Posts con tracción recurrente | 3–5 conversaciones/mes |
| Mes 7–12 | Inbound pipeline activo | 2–4 reuniones/mes |

> LinkedIn es un activo que se aprecia con el tiempo. Los primeros 2 meses se sienten como hablarle a una pared. El mes 6 se sienten como un imán.

---

## Resumen ejecutivo — El sistema completo conectado

```
LINKEDIN                  PIPELINE                  PROPUESTA
───────────────────────────────────────────────────────────────
Contenido →               15–20 conversaciones →    3 conversaciones
Engagement →              activas/mes               previas →
DM estratégico →          CRM en Notion →           40%+ de cierre
2–4 reuniones/mes         Pipeline ponderado $80k+

ONBOARDING                OPERACIÓN INTERNA         CONTRACTORS
───────────────────────────────────────────────────────────────
Confirmación día 0 →      Roles claros →            Bench pre-validado →
Pack bienvenida →         Cadencia Lun/Vie/Mensual/  Activación en 48h →
Kickoff días 3–5 →        Trimestral →              Markup 30–50% →
Status semanal →          Tipos A/B/C →             Calidad controlada
Expansión semana 3–4      Salud de sociedad mensual  por socios

PRICING                   FLUJO DE CAJA             METAS (por socio)
───────────────────────────────────────────────────────────────
Diagnóstico $11–15k       Q1: inversión (-$5k)       Año 1: $50k neto
Core $38–85k              Q2: despegue (+$49k)       Año 2: $75k neto
Retainer $5.5–9k/mes      Q3: velocidad (+$104k)     Año 3: $100k neto
Todo ex-IVA + 13%         Q4: cosecha (+$128k)
```

---

*Documento generado en mayo 2026. Cifras fiscales basadas en Decreto 45333-H y normativa vigente al período fiscal 2026. Tipo de cambio: ¢515/USD. Consultar con contador certificado para estructura final.*
