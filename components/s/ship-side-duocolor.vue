<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="o-qgb6efn"/><path class="etndo0bgq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:ship-side-duocolor" /></template>
<style>
.etndo0bgq {
  d: path("m4 17l-1-5h18l-1 5M5 12V8a2 2 0 0 1 2-2h9l3 6M7 6V3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o-qgb6efn {
  stroke-opacity: 0.4;
  d: path("M2 20c.5.5 1 1 2 1c2 0 2-2 4-2s2 2 4 2s2-2 4-2s2 2 4 2c1 0 1.5-.5 2-1M11 9h.01M14 9h.01");
}

</style>
