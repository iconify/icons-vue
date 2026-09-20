<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rb8ofhiko"/><path class="zugrfydpd"/><path class="x7x2dubhn"/><path class="yl6rclbxh"/><path class="bvxg1_b9x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:painting-duotone-regular" /></template>
<style>
.bvxg1_b9x {
  d: path("m18 6 4 4 -2 2 -4 -4Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rb8ofhiko {
  fill: currentColor;
  d: path("M3 4v12h12V4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.x7x2dubhn {
  d: path("M3 4v12h12V4Z");
}

.yl6rclbxh {
  d: path("m13 15 7 -7");
}

.zugrfydpd {
  fill: currentColor;
  d: path("m18 6 4 4 -2 2 -4 -4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
