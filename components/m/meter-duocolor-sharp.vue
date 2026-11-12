<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ge1buubhj"/><path class="cjftzibmt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:meter-duocolor-sharp" /></template>
<style>
.cjftzibmt {
  d: path("M3 4h18v17H3Zm5-1v1m8-1v1M6 7h12v5H6Zm4 0v5m4-5v5");
}

.ge1buubhj {
  stroke-opacity: 0.4;
  d: path("M8 17h8");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
