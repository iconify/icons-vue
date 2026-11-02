<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lno0446aq"/><path class="q1dwl61-n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tornado-duocolor-round" /></template>
<style>
.lno0446aq {
  stroke-opacity: 0.4;
  d: path("M10 16h6m-7 4h2");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q1dwl61-n {
  d: path("M3 4h18M6 8h12m-9 4h10");
}

</style>
