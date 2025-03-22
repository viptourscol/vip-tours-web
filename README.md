<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>VIP Tours</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <style>
/* Ajustes responsivos adicionales */
@media (max-width: 768px) {
    .jumbotron {
        padding: 60px 15px;
    }
    .display-4 {
        font-size: 2rem;
    }
    .lead {
        font-size: 1rem;
    }
    .section-title {
        font-size: 1.5rem;
    }
    .navbar-brand {
        font-size: 1.2rem;
    }
    .footer p {
        font-size: 0.9rem;
    }
    .list-group-item {
        font-size: 0.9rem;
        padding: 10px;
    }
    .icon-list i, .list-group-item i {
        font-size: 1rem;
    }
}



        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        .jumbotron {
            background-image: url('https://i.ibb.co/nN1VHjyN/entrada.webp');
            background-size: cover;
            background-position: center;
            color: white;
            padding: 120px 0;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.8);
        }
        .navbar-custom {
            background-color: #004080;
        }
        .footer {
            background-color: #004080;
            color: white;
            padding: 15px;
            text-align: center;
        }
        .icon-list li {
            margin-bottom: 10px;
        }
        .section-title {
            color: #004080;
            font-weight: 700;
            margin-bottom: 20px;
        }
        .alert-custom {
            background-color: #ffdddd;
            border-color: #ff5c5c;
            color: #a94442;
        }
    </style>
</head>
<body>

<nav class="navbar navbar-expand-lg navbar-dark navbar-custom">
    <div class="container">
        <a class="navbar-brand" href="#">VIP Tours</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav ms-auto">
                <li class="nav-item"><a class="nav-link" href="#servicios">Servicios</a></li>
                <li class="nav-item"><a class="nav-link" href="#itinerario">Itinerario</a></li>
                <li class="nav-item"><a class="nav-link" href="#recomendaciones">Recomendaciones</a></li>
                <li class="nav-item"><a class="nav-link" href="#contacto">Contacto</a></li>
            </ul>
        </div>
    </div>
</nav>

<div class="jumbotron text-center">
    <h1 class="display-4">Explora Guatapé con VIP Tours</h1>
    <p class="lead">Tu mejor experiencia turística garantizada</p>
</div>

<div class="container my-5" id="servicios">
    <h2 class="section-title text-center">Carta de Servicios</h2>
    <p class="text-center">Un cordial saludo, para nosotros es grato contar con su compañía. Nuestros buses están debidamente limpios y desinfectados.</p>

    <div class="alert alert-custom" role="alert">
        <i class="fa-solid fa-ban"></i> <strong>Prohibido:</strong> Movilizarse dentro del bus. Mal comportamiento podrá ocasionar expulsión inmediata.
    </div>

    <h5><i class="fa-solid fa-map-marker-alt"></i> Lugar y Hora de Recogida</h5>
    <p>Casino Estación Caribe del metro, 6:00 AM (salida 6:30 AM)</p>
    <div class="ratio ratio-16x9 my-4">
        <iframe src="https://maps.google.com/maps?q=6.279248,-75.570058&output=embed" allowfullscreen></iframe>
    </div>
</div>

<div class="container my-5" id="itinerario">
    <h2 class="section-title text-center">Itinerario del Tour</h2>
    <ul class="list-group icon-list">
        <li class="list-group-item"><i class="fa-solid fa-utensils"></i> 8:10 AM: Parada para desayunar restarurante "Sabor Paisa"</li>
        <li class="list-group-item"><i class="fa-solid fa-horse"></i> 9:20 AM - 9:45 AM: Parada granja "El alto del Chocho"</li>
        <li class="list-group-item"><i class="fa-solid fa-archway"></i> 10:30 - 10:50 AM: Visita Réplica Viejo Peñol</li>
        <li class="list-group-item"><i class="fa-solid fa-camera"></i> 11:30 AM - 12:00: Recorrido calles emblemáticas de Guatapé</li>
        <li class="list-group-item"><i class="fa-solid fa-church"></i> 12:00- 12:30 PM: Visita Iglesia y Parque central de Guatapé</li>
        <li class="list-group-item"><i class="fa-solid fa-ship"></i> 12:40 PM - 1:30PM: Tour en Barco Rumbero (Vista panoramica Islas y Condominio)</li>
        <li class="list-group-item"><i class="fa-solid fa-utensils"></i> 2:00 PM: Almuerzo en la piedra restaurante "La Amistad"</li>
        <li class="list-group-item"><i class="fa-solid fa-mountain-sun"></i> 2:30 PM: Tiempo libre Piedra del Peñol</li>
        <li class="list-group-item"><i class="fa-solid fa-bus"></i> 4:30 PM: Regreso a Medellín</li>
    </ul>
</div>

<div class="container my-5" id="recomendaciones">
    <h2 class="section-title text-center">Recomendaciones Importantes</h2>
    
    <div class="alert alert-info text-center" role="alert">
        Por favor ser muy <strong>PUNTUALES</strong> y no separarse del grupo. De esto depende el buen desempeño de todas las actividades programadas.
    </div>

    <ul class="list-group">
        <li class="list-group-item"><i class="fa-solid fa-shirt me-2"></i>Utilizar ropa cómoda para disfrutar mejor el recorrido.</li>
        <li class="list-group-item"><i class="fa-solid fa-sun me-2"></i>Usar bloqueador solar.</li>
        <li class="list-group-item"><i class="fa-solid fa-umbrella me-2"></i>Llevar sombrilla (temporada de lluvias).</li>
        <li class="list-group-item"><i class="fa-solid fa-sunglasses me-2"></i>Usar lentes de sol.</li>
        <li class="list-group-item"><i class="fa-solid fa-id-card me-2"></i>Portar el documento de identificación.</li>
        <li class="list-group-item"><i class="fa-solid fa-clipboard-check me-2"></i>Atender a las sugerencias y recomendaciones de los coordinadores.</li>
        <li class="list-group-item"><i class="fa-solid fa-shield-alt me-2"></i>Proteger los lugares visitados durante el tour.</li>
        <li class="list-group-item"><i class="fa-solid fa-exclamation-triangle me-2"></i>No extraer ningún elemento patrimonial.</li>
    </ul>

    <div class="alert alert-warning mt-4">
        <h5 class="alert-heading"><i class="fa-solid fa-circle-exclamation"></i> Importante Leer con Atención</h5>
        <ul>
            <li>Nosotros ubicamos los pasajeros por orden de llegada. Se acomodan por grupo familiar; personas de tercera edad tienen prioridad.</li>
            <li>El lugar ocupado en los buses durante la ida debe ser el mismo al regreso.</li>
            <li>El tour no incluye gastos no especificados explícitamente.</li>
            <li>Cualquier cancelación o cambio de reserva por fuerza mayor debe estar debidamente justificado.</li>
            <li>Las personas con saldo pendiente deben llevar el valor exacto en efectivo. <strong>Saldo efectivo ✅</strong></li>
            <li>Se reciben pagos con datáfono con tarjetas débito y crédito 💳 (5% adicional de comisión bancaria).</li>
        </ul>
    </div>
</div>


<footer class="footer" id="contacto">
    <div class="container">
        <p><i class="fa-solid fa-envelope"></i> viptours@gmail.com | <i class="fa-solid fa-phone"></i> 300 123 4567 | Medellín, Colombia</p>
        <p>© 2025 VIP Tours. Todos los derechos reservados.</p>
    </div>
</footer>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
