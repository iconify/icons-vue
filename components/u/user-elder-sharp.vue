<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="yk-0sacrz"/><path class="tl8e2gpjy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:user-elder-sharp" /></template>
<style>
.tl8e2gpjy {
  d: path("M3.5 20.25h10.75v-.75c0-3-2.6-5.25-5.75-5.25S2.75 16.5 2.75 19.5v.75zm13.75 0V10.5h3.5V13");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yk-0sacrz {
  cx: 8.5px;
  cy: 7.75px;
  r: 3.5px;
}

</style>
