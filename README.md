# presentaciones_rmarkdown
Una forma útil para hacer presentaciones interactivas y por suspuesto vistosas es con Rmarkdown. 
En este repositorio está un ejemplo sencillo pero muy ilustrativo de cómo se puede hacer una presetnación haciendo uso de diferentes recursos e incorporando textos en formato científico a partir de código LaTex.

Se incluye también un style.css elemental para fijar la imagen del INEGI en la presentación pensando en que en muchas instituciones se cuenta incluso con formatos especiales para este tipo de cosas.

![image](https://github.com/sanalexito/presentaciones_rmarkdown/assets/65984679/77b2a49d-f9e0-4fa6-8d73-1ed067c71d92)

Algo importante es la facilidad para meter ecuaciones
$$
\begin{align*}
  \mbox{Ecuaciones de Maxwell: forma diferencial}\\
  \vec{\nabla} \cdot \vec{E} = \dfrac{\rho}{\epsilon_0}& \qquad \mbox{Ley de Gauss}\\
  \vec{\nabla} \cdot \vec{B} = 0& \qquad \mbox{Ley de Gauss para el campo magnético}\\
  \vec{\nabla}\times\vec{E}=-\dfrac{\partial \vec{B}}{\partial t}& \qquad \mbox{Ley de Faraday}\\
  c^2\vec{\nabla}\times\vec{B} =\dfrac{\vec{J}}{\epsilon_0}+\dfrac {\partial \vec{E}}{\partial t}& \qquad \mbox{1ra Ley de Ampere}\\
  \vec{\nabla}\times \vec{B}=\mu_0\vec{J}+\mu_0 \epsilon_0 \dfrac{\partial \vec{E}}{\partial t}& \qquad \mbox{2da Ley de Ampere}\\
  \\
  \mbox{Ecuaciones de Maxwell: forma integral}\\
  \oint_S \vec{E} \cdot d\vec{s} = \dfrac{q}{\epsilon_0}& \qquad \mbox{Ley de Gauss}\\
  \oint_S \vec{B} \cdot d\vec{s} = 0& \qquad \mbox{Ley de Gauss para el campo magnético}\\
  \oint_C \vec{E} \cdot d\vec{l} = -\dfrac{d}{dt} \int_S \vec{B} \cdot \vec{s}& \qquad \mbox{Ley de Faraday}\\
  c^2 \oint_C \vec{B} \cdot d\vec{l} = \int_S \dfrac{\vec{J} \cdot d\vec{s}}{\epsilon_0} + \dfrac{d}{dt} \int_S \vec{E} \cdot d\vec{s}& \qquad \mbox{1ra Ley de Ampere}\\
  \oint_C \vec{B} \cdot d\vec{l} = \mu_0 \int_S \vec{J} \cdot d\vec{s} + \mu_0 \epsilon_0 \dfrac{d}{dt} \int_S \vec{E} \cdot d\vec{s}& \qquad \mbox{2da Ley de Ampere}
\end{align*}
$$


