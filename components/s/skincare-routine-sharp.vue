<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="q_0q4mbix"/><path class="n4req7kvy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:skincare-routine-sharp" /></template>
<style>
.n4req7kvy {
  d: path("M12 7.25c1.9 2.1 3 3.7 3 5.25a3 3 0 0 1-6 0c0-1.55 1.1-3.15 3-5.25Z");
}

.q_0q4mbix {
  d: path("M21 12a9 9 0 1 1-2.64-6.36L21 8.25m0-5v5h-5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
