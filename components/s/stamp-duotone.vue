<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="frt1ump8y"/><path class="jrjnqrc0o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:stamp-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.frt1ump8y {
  d: path("m159.46 53l-17.78 83h-27.36L96.54 53A24 24 0 0 1 120 24h16a24 24 0 0 1 23.46 29");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jrjnqrc0o {
  d: path("M224 224a8 8 0 0 1-8 8H40a8 8 0 0 1 0-16h176a8 8 0 0 1 8 8m0-80v40a16 16 0 0 1-16 16H48a16 16 0 0 1-16-16v-40a16 16 0 0 1 16-16h56.43L88.72 54.71A32 32 0 0 1 120 16h16a32 32 0 0 1 31.29 38.71L151.57 128H208a16 16 0 0 1 16 16m-103.21-16h14.42l16.43-76.65A16 16 0 0 0 136 32h-16a16 16 0 0 0-15.65 19.35ZM208 184v-40H48v40z");
}

</style>
