<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wg69ldbkn"/><rect class="niln19ngy"/><circle class="ygphxfbhc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:shapes-plus" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.niln19ngy {
  width: 8px;
  height: 8px;
  x: 2.75px;
  y: 13.25px;
  rx: 1.5px;
}

.wg69ldbkn {
  d: path("m12.55 3.58l3.9 5.84q.55.83-.45.83H8q-1 0-.45-.83l3.9-5.84q.55-.83 1.1 0");
}

.ygphxfbhc {
  cx: 17.25px;
  cy: 17.25px;
  r: 4px;
}

</style>
