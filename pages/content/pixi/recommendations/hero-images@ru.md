---
$title: Преобразуйте имеющиеся на странице hero-изображения
$order: 80
tags:
- lcp
---

Предварительная загрузка позволяет вам сообщить браузеру о критически важных ресурсах, которые нужно загрузить как можно скорее — даже раньше, чем они будут обнаружены в HTML-коде. Это особенно полезно для таких ресурсов, как hero-изображения, которые составляют большую долю первоначального рендеринга.<br><br>Используйте [AMP-оптимизатор](https://amp.dev/documentation/guides-and-tutorials/optimize-and-measure/amp-optimizer-guide/), поскольку он автоматически обнаруживает hero-изображения страницы и добавляет для них теги предварительной загрузки. Он также позволяет использовать атрибут `data-hero` для указания изображений на странице вручную.