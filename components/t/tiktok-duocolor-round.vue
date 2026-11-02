<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="kh-prx2jc"/><path class="quf2x8v8o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tiktok-duocolor-round" /></template>
<style>
.kh-prx2jc {
  stroke-opacity: 0.4;
  d: path("M16 10v4.5a6.5 6.5 0 1 1-8-6.325V12.5C6.078 13.942 7.097 17 9.5 17a2.5 2.5 0 0 0 2.5-2.5V3h4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.quf2x8v8o {
  d: path("M16 3a5 5 0 0 0 5 5v4a11.1 11.1 0 0 1-5-2");
}

</style>
