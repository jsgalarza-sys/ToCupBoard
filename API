console.log('Script cargado correctamente');

// Simulación de token JWT
const token = 'simulado_jwt_token';

// Simulación de obtención de productos
async function obtenerProductos() {
  console.log('Simulando obtención de productos...');

  // Simulamos una respuesta de la API
  const productos = [
    { id: 1, nombre: 'Camiseta Local', precio: '$20' },
    { id: 2, nombre: 'Gorra Local', precio: '$15' },
    { id: 3, nombre: 'Bolso Local', precio: '$25' }
  ];

  // Mostramos en consola y en pantalla
  console.log('Productos:', productos);
  document.getElementById('resultado').innerText = 'Productos obtenidos:\n' +
    productos.map(p => `• ${p.nombre} - ${p.precio}`).join('\n');
  alert('Productos obtenidos.');
}

// Simulación de envío de formulario
async function enviarFormulario() {
  console.log('Simulando envío de formulario...');

  const datos = {
    nombre: 'Jordan',
    email: 'jordan@email.com',
    mensaje: 'Hola, quiero más info sobre sus productos'
  };

  // Simulamos una respuesta del servidor
  setTimeout(() => {
    console.log('Formulario enviado:', datos);
    document.getElementById('resultado').innerText =
      `Formulario enviado:\nNombre: ${datos.nombre}\nEmail: ${datos.email}\nMensaje: ${datos.mensaje}`;
    alert('Formulario simulado enviado.');
  }, 1000);
}
