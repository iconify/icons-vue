<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="kd2_tebys"/><path class="z39kxgb4s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:snail-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.kd2_tebys {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M2 12a7 7 0 0 1 6.498-6.982A7.003 7.003 0 0 1 15.93 11H19a1 1 0 0 1 1 1v5c0 2.248-1.752 4-4 4H3a1 1 0 0 1-1-1Z");
}

.z39kxgb4s {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 20v-8a6 6 0 1 1 12 0a4 4 0 1 1-8 0a2 2 0 1 1 4 0m-8 8h13c1.7 0 3-1.3 3-3V8m0 0l-2-4m2 4l2-4");
}

</style>
