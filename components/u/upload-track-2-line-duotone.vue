<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="dhsvhev9z"/><circle class="x6tlt5s8q"/><path class="ykkyycbio"/><path class="n-y7-h-tz"/><circle class="doy9q4b5f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:upload-track-2-line-duotone" /></template>
<style>
.dhsvhev9z {
  d: path("M13 15V11V7");
}

.doy9q4b5f {
  cx: 12px;
  cy: 12px;
  r: 10px;
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n-y7-h-tz {
  stroke-linejoin: round;
  d: path("M18 22V15M15.5 17.5L18 15L20.5 17.5");
}

.x6tlt5s8q {
  cx: 11px;
  cy: 15px;
  r: 2px;
}

.ykkyycbio {
  d: path("M16 10C14.3431 10 13 8.65685 13 7");
}

</style>
