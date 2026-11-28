<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="v5i4a1bda"/><path clip-rule="evenodd" class="d7nwc0bnr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:router-off-sharp" /></template>
<style>
.d7nwc0bnr {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9 16C9 16.5523 8.552 17 8 17C7.448 17 7 16.5523 7 16C7 15.4477 7.448 15 8 15C8.552 15 9 15.4477 9 16Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.v5i4a1bda {
  d: path("M20 20H2V12H12M19.189 3.2425L17 12H22V17.3431M7 12L5.333 5.3333M1.707 1.7071L22.293 22.293");
}

</style>
