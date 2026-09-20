<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="iqgx6tbhv"/><path class="q688ovtow"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:vector-three-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.iqgx6tbhv {
  d: path("M232 40v96l-67.31 67.31a16 16 0 0 1-11.32 4.69H48V102.63a16 16 0 0 1 4.69-11.32L120 24h96a16 16 0 0 1 16 16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.q688ovtow {
  d: path("m237.66 141.66l-32 32a8 8 0 0 1-11.32-11.32L212.69 144h-89.38l-56 56H96a8 8 0 0 1 0 16H48a8 8 0 0 1-8-8v-48a8 8 0 0 1 16 0v28.69l56-56V43.31L93.66 61.66a8 8 0 0 1-11.32-11.32l32-32a8 8 0 0 1 11.32 0l32 32a8 8 0 0 1-11.32 11.32L128 43.31V128h84.69l-18.35-18.34a8 8 0 0 1 11.32-11.32l32 32a8 8 0 0 1 0 11.32");
}

</style>
