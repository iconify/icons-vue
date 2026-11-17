<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n57he_b_m"/><path class="ivk6cei0x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:target-arrow-duocolor" /></template>
<style>
.ivk6cei0x {
  d: path("M21 12a9 9 0 1 1-9-9m5 9a5 5 0 1 1-5-5");
}

.n57he_b_m {
  stroke-opacity: 0.4;
  d: path("m12 12l9-9m-4 0v4h4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
