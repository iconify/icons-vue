<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="hidfxz0es"/><path class="dr-7-cpfy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:number-zero-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.dr-7-cpfy {
  d: path("M183.25 63.2C170.25 42.79 151.15 32 128 32S85.75 42.79 72.75 63.2C62 80.18 56 103.19 56 128s6 47.82 16.75 64.8c13 20.41 32.1 31.2 55.25 31.2s42.25-10.79 55.25-31.2c10.8-17 16.75-40 16.75-64.8s-5.95-47.82-16.75-64.8M128 208c-38.68 0-56-40.18-56-80s17.32-80 56-80s56 40.18 56 80s-17.32 80-56 80");
}

.hidfxz0es {
  d: path("M216 40v176a16 16 0 0 1-16 16H56a16 16 0 0 1-16-16V40a16 16 0 0 1 16-16h144a16 16 0 0 1 16 16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
