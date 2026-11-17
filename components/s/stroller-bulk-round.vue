<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="al0hoy1sc"/><path class="fuwojr9ij"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:stroller-bulk-round" /></template>
<style>
.al0hoy1sc {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21.868 10.497a9.057 9.057 0 0 1-12.363 3.37a9.06 9.06 0 0 1-3.372-3.372A1 1 0 0 1 7 9h7V4a1 1 0 0 1 1-1a6.9 6.9 0 0 1 2.725.551A6.9 6.9 0 0 1 19.95 5.05A6.97 6.97 0 0 1 22 10a1 1 0 0 1-.132.496ZM7.236 17.832a3 3 0 1 1 5.527 2.338a3 3 0 0 1-5.527-2.338m8 0a3 3 0 1 1 5.527 2.338a3 3 0 0 1-5.527-2.338M9.29 19.704l.001.001l.002.002l.002.002a1 1 0 0 0 1.41 0l.002-.002l.002-.002l.001-.001a1 1 0 0 0 0-1.408l-.001-.001l-.002-.002l-.002-.002a1 1 0 0 0-1.41 0l-.002.002l-.002.002l-.001.001a1 1 0 0 0 0 1.408m8 0l.001.001l.002.002l.002.002l.001.001a1 1 0 0 0 1.408 0l.001-.001l.002-.002l.002-.002l.001-.001a1 1 0 0 0 0-1.408l-.001-.001l-.002-.002l-.002-.002l-.001-.001a1 1 0 0 0-1.408 0l-.001.001l-.002.002l-.002.002l-.001.001a1 1 0 0 0 0 1.408");
}

.cuyn6tgcc {
  fill: currentColor;
}

.fuwojr9ij {
  d: path("M14 4a1 1 0 0 1 1-1c1.862 0 3.636.731 4.95 2.05a7 7 0 0 1 1.5 2.225c.365.862.553 1.789.55 2.725a1 1 0 0 1-1 1H6.997a1 1 0 0 1-.925-.629L4.323 6H3a1 1 0 0 1 0-2h2c.409 0 .777.249.928.629L7.677 9H14Zm5.901 5A5.02 5.02 0 0 0 16 5.099V9ZM9 16.171V13a1 1 0 0 1 2 0v3.171a3 3 0 1 1-2 0m8 0V13a1 1 0 0 1 2 0v3.171a3 3 0 1 1-2 0M10 18a1 1 0 1 0 0 2a1 1 0 0 0 0-2m8 0a1 1 0 1 0 0 2a1 1 0 0 0 0-2");
}

</style>
