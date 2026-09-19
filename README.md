# NovaGo Delivery

Sistema web de gestion de minimarket con delivery propio.

## Integrantes
- Conislla Lavado Cesar Jesus - U23264049
- Ruben Walter Vivas Jiménez - U18209770

## Estado del proyecto

— Avance de Proyecto Final 1 (APF1)

- [x] apps/users — autenticación y roles (CLIENT, DELIVERY, ADMIN)
- [x] apps/products — catálogo de productos y control de inventario
- [ ] apps/orders — gestión de pedidos y carrito
- [ ] apps/payments — métodos de pago y comprobantes
- [ ] apps/tracking — geolocalización y seguimiento

## Instrucciones de ejecución

1. Crear entorno virtual
python -m venv venv

2. activar el entorno virtual
venv\Scripts\Activate.ps1

3. instalar dependencias
pip install -r requirements.txt

4. aplicar las migraciones
python manage.py migrate

5. Crear superUsuario
python manage.py createsuperuser

6. Correr el servicio
python manage.py runserver