<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Gabriel Glatz</title>
  
  <!-- Importando a biblioteca Particle.js -->
  <script src="https://cdn.jsdelivr.net/particles.js/2.0.0/particles.min.js"></script>

  <style>
    /* Estilo para o container das partículas */
    #particles-js {
      position: absolute;
      width: 100%;
      height: 100%;
      background-color: #1d1d1d;
      background-size: cover;
      background-position: 50% 50%;
      z-index: -1;
    }

    /* Estilo da página */
    body, html {
      margin: 0;
      padding: 0;
      width: 100%;
      height: 100%;
      font-family: Arial, sans-serif;
      color: white;
    }

    /* Centralizando o conteúdo */
    .content {
      position: relative;
      z-index: 1;
      text-align: center;
      top: 50%;
      transform: translateY(-50%);
    }

    h1 {
      font-size: 3rem;
    }

    h4 {
      font-size: 1.2rem;
      margin: 1rem;
    }

    .social-icons img {
      margin: 10px;
    }
  </style>
</head>
<body>

  <!-- Container das partículas -->
  <div id="particles-js"></div>

  <!-- Conteúdo principal da página -->
  <div class="content">
    <h1>Olá! Eu sou o Gabriel Glatz 😴</h1>
    <div>
      <h4>Sou apaixonado por tecnologia e programação. Atualmente, estou focado em aprimorar minhas habilidades e sou Jovem Aprendiz no Grupo Malwee.</h4>
      <h4>Com uma combinação de habilidades, dedicação e um forte desejo de crescimento, estou confiante de que posso agregar valor em diversas equipes de trabalho.</h4>
    </div>

    <!-- Contador de Visualizações -->
    <div align="center">
      <img src="https://komarev.com/ghpvc/?username=glatztp&color=ff0000&label=Visitantes&style=flat-square" alt="Visualizações do Perfil"/>
    </div>

    <h2>Ferramentas e Tecnologias 💻</h2>
    <div style="display: inline_block" align="center">
      <br>
      <img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54"/>
      <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>
      <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"/>
      <img src="https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E"/>
      <img src="https://img.shields.io/badge/MicroPython-2B2728?style=for-the-badge&logo=micropython&logoColor=white"/>
      <img src="https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white"/>
    </div>

    <h2>Mídias Sociais</h2>
    <div class="social-icons" align="center">
      <a href="https://www.linkedin.com/in/gabriel-glatz/" target="_blank">
        <img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white" alt="LinkedIn">
      </a>
      <a href="https://www.instagram.com/glatz.tp/" target="_blank">
        <img src="https://img.shields.io/badge/Instagram-%23E4405F.svg?logo=Instagram&logoColor=white" alt="Instagram">
      </a>
      <a href="https://github.com/glatztp" target="_blank">
        <img src="https://img.shields.io/badge/GitHub-%23121011.svg?logo=github&logoColor=white" alt="GitHub">
      </a>
    </div>
  </div>

  <!-- Script de configuração das partículas -->
  <script>
    particlesJS('particles-js', {
      "particles": {
        "number": {
          "value": 80,
          "density": {
            "enable": true,
            "value_area": 800
          }
        },
        "color": {
          "value": "#ffffff"
        },
        "shape": {
          "type": "circle",
          "stroke": {
            "width": 0,
            "color": "#000000"
          },
          "polygon": {
            "nb_sides": 5
          }
        },
        "opacity": {
          "value": 0.5,
          "random": false,
          "anim": {
            "enable": false,
            "speed": 1,
            "opacity_min": 0.1,
            "sync": false
          }
        },
        "size": {
          "value": 5,
          "random": true,
          "anim": {
            "enable": false,
            "speed": 40,
            "size_min": 0.1,
            "sync": false
          }
        },
        "line_linked": {
          "enable": true,
          "distance": 150,
          "color": "#ffffff",
          "opacity": 0.4,
          "width": 1
        },
        "move": {
          "enable": true,
          "speed": 6,
          "direction": "none",
          "random": false,
          "straight": false,
          "out_mode": "out",
          "bounce": false,
          "attract": {
            "enable": false,
            "rotateX": 600,
            "rotateY": 1200
          }
        }
      },
      "interactivity": {
        "detect_on": "canvas",
        "events": {
          "onhover": {
            "enable": true,
            "mode": "repulse"
          },
          "onclick": {
            "enable": true,
            "mode": "push"
          },
          "resize": true
        },
        "modes": {
          "grab": {
            "distance": 400,
            "line_linked": {
              "opacity": 1
            }
          },
          "bubble": {
            "distance": 400,
            "size": 40,
            "duration": 2,
            "opacity": 8,
            "speed": 3
          },
          "repulse": {
            "distance": 200,
            "duration": 0.4
          },
          "push": {
            "particles_nb": 4
          },
          "remove": {
            "particles_nb": 2
          }
        }
      },
      "retina_detect": true
    });
  </script>

</body>
</html>
