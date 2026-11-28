<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="sgcmhac9p"/><path class="i88y1sd6n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:router-off" /></template>
<style>
.i88y1sd6n {
  fill: currentColor;
  d: path("M9 16C9 16.5523 8.5523 17 8 17C7.4477 17 7 16.5523 7 16C7 15.4477 7.4477 15 8 15C8.5523 15 9 15.4477 9 16Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.sgcmhac9p {
  d: path("M20 20L4 20C2.8954 20 2 19.1046 2 18L2 14C2 12.8954 2.8954 12 4 12L12 12M17.6569 12L20 12C21.1046 12 22 12.8954 22 14L22 16.3431M7 12L5.3333 5.3333M17.1314 11.4745L19 4M2 2L22 22");
}

</style>
