<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="skgvgti8z"/><path class="elyihdc9x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:tag-simple-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.elyihdc9x {
  d: path("M246.66 123.56L201 55.13A15.94 15.94 0 0 0 187.72 48H40a16 16 0 0 0-16 16v128a16 16 0 0 0 16 16h147.72a16 16 0 0 0 13.28-7.12l45.63-68.44a8 8 0 0 0 .03-8.88M187.72 192H40V64h147.72l42.66 64Z");
}

.skgvgti8z {
  d: path("m240 128l-45.62 68.44a8 8 0 0 1-6.66 3.56H40a8 8 0 0 1-8-8V64a8 8 0 0 1 8-8h147.72a8 8 0 0 1 6.66 3.56Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
