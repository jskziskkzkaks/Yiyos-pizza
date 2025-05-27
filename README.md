# Yiyos-pizza
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Yiyos Pizza – Actopan, Hidalgo</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; background-color: #fff8f0; }
        header { background-color: #d32f2f; color: white; padding: 20px; text-align: center; }
        section { padding: 20px; }
        h2 { color: #d32f2f; }
        .contact-form { max-width: 400px; margin: auto; }
        .contact-form input, .contact-form textarea { width: 100%; padding: 10px; margin: 5px 0; }
        .contact-form button { background-color: #d32f2f; color: white; padding: 10px; border: none; cursor: pointer; }
        footer { background-color: #f1f1f1; text-align: center; padding: 10px; }
    </style>
</head>
<body>
    <header>
        <h1>Yiyos Pizza</h1>
        <p>Sabor auténtico en Actopan, Hidalgo</p>
    </header>
    <section>
        <h2>Información</h2>
        <p><strong>Dirección:</strong> Calle Guadalupe Victoria LB, Col. Obrera, 42500 Actopan, Hidalgo</p>
        <p><strong>Teléfono:</strong> 772 727 4420</p>
        <p><strong>Horario:</strong> Lunes a Domingo, de 9:00 a 23:00 hrs</p>
    </section>
    <section>
        <h2>Menú Destacado</h2>
        <ul>
            <li>Pizzas Clásicas: Pepperoni, Hawaiana, Vegetariana</li>
            <li>Especialidades: Pizzas caseras con ingredientes frescos</li>
            <li>Complementos: Hamburguesas, hot dogs y pollos rostizados para llevar</li>
        </ul>
    </section>
    <section>
        <h2>Contáctanos</h2>
        <div class="contact-form">
            <form action="mailto:contacto@yiyospizza.com" method="post" enctype="text/plain">
                <input type="text" name="nombre" placeholder="Tu nombre" required>
                <input type="email" name="email" placeholder="Tu correo electrónico" required>
                <textarea name="mensaje" rows="5" placeholder="Escribe tu mensaje aquí..." required></textarea>
                <button type="submit">Enviar</button>
            </form>
        </div>
    </section>
    <footer>
        <p>&copy; 2025 Yiyos Pizza. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
