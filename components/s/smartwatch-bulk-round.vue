<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ib8ghnj8c"/><path class="mxj72p-zr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:smartwatch-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ib8ghnj8c {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 10a5 5 0 0 1 5-5h4a5 5 0 0 1 5 5v4a5 5 0 0 1-1.464 3.536A5 5 0 0 1 14 19h-4a5 5 0 0 1-5-5Z");
}

.mxj72p-zr {
  d: path("M8 4.999c0-.796.317-1.56.881-2.122A3 3 0 0 1 11 2h2.001c1.657.001 3 1.343 2.999 3v1a1 1 0 0 1-2 0V4.998A1 1 0 0 0 13 4h-2a.997.997 0 0 0-1 1v1a1 1 0 0 1-2 0ZM11 20h2a1 1 0 0 0 1-1v-1a1 1 0 0 1 2 0v1a3 3 0 0 1-3 3h-2a3 3 0 0 1-3-3v-1a1 1 0 0 1 2 0v1a1 1 0 0 0 1 1");
}

</style>
