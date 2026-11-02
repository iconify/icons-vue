<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="sju9b47kv"/><path class="cz5g47vfa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:trash-full-duocolor-round" /></template>
<style>
.cz5g47vfa {
  d: path("M6 6v11a4 4 0 0 0 4 4h4a4 4 0 0 0 4-4V6M4 6h16M8 6a3 3 0 0 1 3-3h2a3 3 0 0 1 3 3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.sju9b47kv {
  stroke-opacity: 0.4;
  d: path("M10 10v7m4-7v7");
}

</style>
