<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="j7phtvv5f"/><path class="p-74fg5cj"/><path class="vz5_16nyg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:subscribe-outline-regular" /></template>
<style>
.j7phtvv5f {
  d: path("M4 19a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p-74fg5cj {
  d: path("M5 12a7 7 0 0 1 7 7");
}

.vz5_16nyg {
  d: path("M5 6a13 13 0 0 1 13 13");
}

</style>
