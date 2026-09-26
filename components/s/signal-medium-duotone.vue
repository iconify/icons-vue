<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="cyawe5bba"/><path class="qrvxkc7do"/><path class="dno4_nblm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:signal-medium-duotone" /></template>
<style>
.cyawe5bba {
  stroke-linejoin: miter;
  d: path("M12 20L12 12M7 20L7 16");
}

.dno4_nblm {
  fill: currentColor;
  d: path("M3 20C3 20.5523 2.5523 21 2 21C1.4477 21 1 20.5523 1 20C1 19.4477 1.4477 19 2 19C2.5523 19 3 19.4477 3 20Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qrvxkc7do {
  stroke-linejoin: miter;
  stroke-opacity: 0.4;
  d: path("M22 20L22 4M17 20L17 8");
}

</style>
