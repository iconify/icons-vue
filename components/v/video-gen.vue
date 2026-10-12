<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="mza817zhn"/><path class="xzjtmzrol"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:video-gen" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mza817zhn {
  width: 12px;
  height: 12px;
  x: 2.75px;
  y: 6px;
  rx: 2.5px;
}

.xzjtmzrol {
  d: path("m18.36 9.81l2.28-1.62q.61-.44.61.31v7q0 .75-.61.31l-2.28-1.62q-.61-.44-.61-1.19v-2q0-.75.61-1.19M8.75 8.5q.42 3.08 3.5 3.5q-3.08.42-3.5 3.5q-.42-3.08-3.5-3.5q3.08-.42 3.5-3.5");
}

</style>
