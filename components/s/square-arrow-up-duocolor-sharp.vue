<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="x-z7qobzv"/><path class="j_psw1y4g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-arrow-up-duocolor-sharp" /></template>
<style>
.j_psw1y4g {
  d: path("M3 3h18v18H3Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.x-z7qobzv {
  stroke-opacity: 0.4;
  d: path("m15 11l-3-3l-3 3m3-3v8");
}

</style>
