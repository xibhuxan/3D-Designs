# 🎨 3D-Designs | OpenSCAD Portfolio

### 🛠️ Biblioteca de diseños paramétricos para ingeniería, fabricación y prototipado rápido

---

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![OpenSCAD version](https://img.shields.io/badge/OpenSCAD-2.0.0+-orange.svg)](https://www.openscad.org/)
[![GitHub forks](https://img.shields.io/github/forks/xibhuxan/3D-Designs)](https://github.com/xibhuxan/3D-Designs/network)
[![GitHub stars](https://img.shields.io/github/stars/xibhuxan/3D-Designs)](https://github.com/xibhuxan/3D-Designs/stargazers)
[![3D Printing](https://img.shields.io/badge/3D%20Printing-Ready-green.svg)](#)
[![FABLAB](https://img.shields.io/badge/Fabricación-Local-ff69b4.svg)](https://www.fablabes.com/)

**⭐ Star este repositorio si te gusta el diseño paramétrico y la ingeniería abierta**


---

## 📦 ¿Qué es esto?

Colección de **diseños generativos y paramétricos** creados con **[OpenSCAD](https://www.openscad.org/)**, enfocada en:

- ✅ **Diseño de cajas eléctricas** industriales y seguras
- ✅ **Arandillas para tubos** de protección mecánica
- ✅ **Tapa de llanta** y componentes de fijación
- ✅ **Cajas con esquinas reforzadas** para instalaciones robustas

Cada diseño utiliza **variables paramétricas** que permiten adaptar dimensiones sin modificar la lógica del modelo. Ideal para ingenieros, makers y prototipado rápido.

---

## 🎯 ¿Para quién es este repositorio?

- 👨‍💻 **Ingenieros eléctricos** que buscan soluciones personalizables
- 🛠️ **Makers** y entusiastas de la impresión 3D
- 🏭 **Fabricantes** que necesitan piezas paramétricas escalables
- 📚 **Educadores** para enseñar diseño paramétrico con OpenSCAD

> ⚠️ **Disclaimer**: Los diseños de cajas eléctricas tienen fines **educacionales**. Se requiere experiencia con cables, voltajes y normativa local antes de implementar.

---

## 🗂️ Estructura del Proyecto

```
3D-Designs/
├── README.md                      # Documentación principal
├── LICENSE                        # Licencia MIT
└── OpenScad/
    ├── EjemploObjeto.scad         # Demostración inicial
    ├── CajaElectrica/             # Cajas para componentes eléctricos
    │   ├── CajaEntera.scad        # Diseño modular con variables
    │   ├── *.stl                  # Exportados para impresión
    │   ├── *.gcode                # G-code para impresión
    │   └── [README, imágenes]/
    ├── ArandelaTubo/              # Arandillas de protección tubular
    │   ├── ArandelaTubo.scad
    │   └── *.stl, *.gcode
    ├── CajaEsquina/               # Esquinas reforzadas
    │   ├── CajaEsquina.scad
    │   └── *.stl, *.gcode
    ├── TapaLlanta/                # Tapas para bases
    │   ├── TapaLlanta.scad
    │   └── *.gcode
    └── TapaTubo/                  # Tapas para tubos
        ├── TapaTubo.scad
        └── *.gcode, *.stl
```

---

## 🚀 ¿Cómo usar estos diseños?

### Prerrequisitos

- [OpenSCAD 2.0.0+](https://www.openscad.org/) (Windows, macOS, Linux)
- [PrusaSlicer](https://www.prusaprinters.cloud/) o similar para G-code
- Impresora 3D con capacidades de 220×220×200mm (recomendado)

### Pasos Rápidos

```bash
# 1. Clona el repositorio
git clone https://github.com/xibhuxan/3D-Designs.git
cd 3D-Designs

# 2. Abre los archivos .scad en OpenSCAD
#    (Usa OpenSCAD para renderizar y exportar STL)

# 3. Exporta el STL y procesa en PrusaSlicer
#    Luego genera el G-code para tu impresora
```

---

## ⚙️ Personalización

Todos los diseños utilizan **variables paramétricas** para facilitar ajustes:

### Variables principales (`CajaElectrica/CajaEntera.scad`)

| Variable | Descripción | Valor por defecto |
|----------|-------------|-------------------|
| `objetoParaMostrar` | Selecciona el diseño a renderizar | `0` |
| `baseLadoA` | Dimensión lateral (mm) | `16` |
| `baseLadoB` | Dimensión frontal (mm) | `19.6` |
| `gruesoBase` | Grosor base (mm) | `0.3` |
| `altoParedes` | Altura paredes (mm) | `6.5` |
| `gruesoParedes` | Grosor paredes (mm) | `0.3` |
| `radioTornillo` | Radio tornillo (mm) | `0.3` |
| `radioSeparador` | Radio separador rail (mm) | `1` |

> 💡 **Tip**: Modifica las variables y renderiza con `F5`. Exporta STL con `F6`.

---

## 📸 Galería de Diseños

### 📦 Caja EléCTRica

Diseño modular para encapsulación de componentes eléctricos con separadores tipo rail, pilares para varillas roscadas y tapas personalizables.

![](OpenScad/CajaElectrica/1.jpg)  
![](OpenScad/CajaElectrica/2.jpg)  
![](OpenScad/CajaElectrica/3.jpg)

---

## 🛡️ Seguridad

- ⚡ **Electricidad con riesgos**: Verifica tensiones y normativas antes de implementar
- 📏 **Sin certificación IP/IK**: Los diseños son educativos, no certificados
- 🔧 **Materiales recomendados**: ABS, PLA+, PETG para entornos industriales

---

## 🌟 Contribución

¡Bienvenido a contribuir! Sigue estas guías:

1. **Fork** el repositorio
2. **Clona** tu copia
3. **Modifica** los diseños o añade nuevos
4. **Crea una Pull Request** con tus cambios

```bash
git clone https://github.com/xibhuxan/3D-Designs.git
cd 3D-Designs
git checkout -b feature-nuevo-diseño
# Edita y añade cambios
git commit -m "Añade nuevo diseño"
git push origin feature-nuevo-diseño
```

---

## 📜 Licencia

Este proyecto está disponible bajo la licencia **[MIT](LICENSE)**. Libres para uso comercial, educativo y personal.

---

## 📬 Contacto y Redes

- 📧 **Correo**: [xibhuxan@example.com](mailto:xibhuxan@example.com)
- 🐦 **Twitter/X**: [@xibhuxan](https://twitter.com/xibhuxan)
- 💼 **LinkedIn**: [xibhuxan](https://linkedin.com/in/xibhuxan)
- 🐙 **GitHub**: [@xibhuxan](https://github.com/xibhuxan)

