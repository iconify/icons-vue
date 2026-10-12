<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="r0u3ypbyz"/><path class="gdgesebuz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:wheelchair" /></template>
<style>
.gdgesebuz {
  d: path("M9.75 8.25v5.25h5.75l2.25 5.75h2.5M5.36 11.86a5.5 5.5 0 1 0 8.65 6.64");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r0u3ypbyz {
  cx: 9.75px;
  cy: 4.75px;
  r: 1.75px;
}

</style>
