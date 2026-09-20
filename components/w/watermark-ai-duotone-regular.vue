<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="yxow7abeb"/><path class="abnm6smsv"/><path class="q9p0j-bua"/><path class="o1pyalbqf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:watermark-ai-duotone-regular" /></template>
<style>
.abnm6smsv {
  d: path("M13 3H6v18h12V8");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o1pyalbqf {
  d: path("m8 16 2 -2 2 2 2 -2 2 2");
}

.q9p0j-bua {
  d: path("m8 11 2 -2 2 2 2 -2 2 2");
}

.yxow7abeb {
  fill: currentColor;
  d: path("M13 3H6v18h12V8");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
