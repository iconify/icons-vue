<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ndzpn0bnu"/><path class="xlm4t5bbx"/><path class="m1v1ebb5g"/><path class="rynjb5q0q"/><path class="mtwnxab5w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:wheelchair-duotone-regular" /></template>
<style>
.m1v1ebb5g {
  d: path("M3 16a6 6 0 1 0 12 0 6 6 0 1 0 -12 0");
}

.mtwnxab5w {
  d: path("M8 3v6h7v4h4");
}

.ndzpn0bnu {
  fill: currentColor;
  d: path("M3 16a6 6 0 1 0 12 0 6 6 0 1 0 -12 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rynjb5q0q {
  d: path("M7 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.xlm4t5bbx {
  fill: currentColor;
  d: path("M7 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
