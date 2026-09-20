<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="g1q21ib8z"/><path class="m2c69rbrn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:shower-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.g1q21ib8z {
  d: path("m184 72l-22.09 129.31a8 8 0 0 1-13.54 4.34l-98-98a8 8 0 0 1 4.34-13.54Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.m2c69rbrn {
  d: path("M64 236a12 12 0 1 1-12-12a12 12 0 0 1 12 12m20-44a12 12 0 1 0 12 12a12 12 0 0 0-12-12m-64 0a12 12 0 1 0 12 12a12 12 0 0 0-12-12m32-32a12 12 0 1 0 12 12a12 12 0 0 0-12-12M256 40a8 8 0 0 1-8 8h-28.69l-27.85 27.86l-21.66 126.79a16 16 0 0 1-27.09 8.66l-98-98a16 16 0 0 1 8.69-27.1l126.74-21.67l30.2-30.2A8 8 0 0 1 216 32h32a8 8 0 0 1 8 8m-81.79 41.79L56 102l98 98Z");
}

</style>
