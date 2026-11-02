<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qakt9_bfe"/><path class="ra990dx0j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:trash-duocolor-round" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qakt9_bfe {
  stroke-opacity: 0.4;
  d: path("M4 6h16M8 6a3 3 0 0 1 3-3h2a3 3 0 0 1 3 3");
}

.ra990dx0j {
  d: path("M6 6v11a4 4 0 0 0 4 4h4a4 4 0 0 0 4-4V6");
}

</style>
