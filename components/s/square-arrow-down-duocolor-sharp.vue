<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="luej32qfe"/><path class="j_psw1y4g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-arrow-down-duocolor-sharp" /></template>
<style>
.j_psw1y4g {
  d: path("M3 3h18v18H3Z");
}

.luej32qfe {
  stroke-opacity: 0.4;
  d: path("m9 13l3 3l3-3m-3 3V8");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
