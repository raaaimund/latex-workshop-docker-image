# latex-builder

This [Dockerfile](Dockerfile) was created to build a latex document together with the [Visual Studio Code](https://code.visualstudio.com) extension [LaTeX Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop).

Be aware, the image's size is __3.395GB__.

Just set the following settings

```json
{
    "latex-workshop.docker.image.latex": "raaaimund/latex-builder",
    "latex-workshop.docker.enabled": true
}
```