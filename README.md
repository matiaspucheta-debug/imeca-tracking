# Imeca Lumber — Live Delivery Tracking Portal

Portal Web interactivo de seguimiento de entregas en tiempo real (estilo DoorDash / Uber) para clientes de Imeca Lumber.

- **URL de Producción**: `https://matiaspucheta-debug.github.io/imeca-tracking/`
- **Uso**: `https://matiaspucheta-debug.github.io/imeca-tracking/?order={orderId}&destLat={destLat}&destLng={destLng}&destAddr={encodedAddress}&truckLat={truckLat}&truckLng={truckLng}&packages={packages}&dropoff={dropoff}&driver={driverName}&truck={truckNumber}`

## Características
- Mapa en pantalla completa con Carto Voyager High-DPI y enrutamiento vial OSRM.
- Camión animado con halo de radar dorado y avance en tiempo real.
- Tarjeta flotante con ETA dinámico, Stepper de 4 etapas y botones de contacto directo al chofer (Llamar / SMS).
