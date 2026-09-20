<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="vu857bc-m"/><g class="jcyaq397j"><circle class="rarb4f01a"/><circle class="ie357eb4u"/><circle class="u-yskabuz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:speech-balloon" /></template>
<style>
.ie357eb4u {
  cx: 64.6px;
  cy: 57px;
  r: 8px;
}

.jcyaq397j {
  fill: var(--svg-color--54646d, #54646d);
}

.rarb4f01a {
  cx: 32.6px;
  cy: 57px;
  r: 8px;
}

.u-yskabuz {
  cx: 95.4px;
  cy: 57px;
  r: 8px;
}

.vu857bc-m {
  fill: var(--svg-color--fff, #fff);
  stroke: var(--svg-color--000, #000);
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--6px, 6px);
  d: path("M63.65 8.07C20.99 8.29 3.72 30.53 3.39 58.23c-.18 15.47 9.79 28.83 25.07 36.98c7.45 5.27-1.42 22.54-8.52 26.95c0 0 25.1-1.71 32.02-19.4c3.82.56 7.75.85 11.78.85c33.28 0 60.17-17.68 60.17-45.38S106.72 7.86 63.65 8.07z");
}

</style>
