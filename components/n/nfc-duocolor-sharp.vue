<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ljr7_8--k"/><path class="j_psw1y4g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:nfc-duocolor-sharp" /></template>
<style>
.j_psw1y4g {
  d: path("M3 3h18v18H3Z");
}

.ljr7_8--k {
  stroke-opacity: 0.4;
  d: path("M8 21V8l8 8V3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
