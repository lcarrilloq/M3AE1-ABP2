# Proyecto BEM – M3AE2 ABP2

Este proyecto corresponde a la actividad **"Metodologías de organización y modularización de estilos"** del módulo 3. Su objetivo es implementar buenas prácticas de organización de estilos mediante la metodología BEM (Bloques, Elementos y Modificadores), generando una interfaz clara, modular y escalable.


Metodología BEM Aplicada

Se definieron los siguientes bloques y sus respectivos elementos:

- `header`
  - `header__container`
  - `header__logo`
  - `header__nav`
    - `nav__list`
    - `nav__item`
    - `nav__item--active` (modificador)
    - `nav__item--disabled` (modificador)
- `main`
  - `main__article`
    - `article__title`
     - `article__image`
     - `article__text`
  - `main__gallery`
    - `gallery__title`
    - `gallery__grid`
    - `gallery__image`
  - `main__contact`
    - `contact__title`
    - `contact__form`
    - `contact__field`
    - `contact__label`
    - `form__input`
    - `contact__button`
- `footer`
  - `footer_content`
  - `footer__info`
  - `footer_text`
  - `footer__social`
  - `footer__link`
  - `footer__icon`


  Estructura del Proyecto

```
M3AE2-ABP-2/
├── css/
│   └── styles.css
├── html/
│   └── index.html
└── README.md
```