<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="hrbw6pe9j"/><path class="h7nz3zbpa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:zero-day" /></template>
<style>
.h7nz3zbpa {
  d: path("M8 2.75v3.5m8-3.5v3.5M2.75 9.5h18.5M12 12c1.4 0 2.25 1.2 2.25 3.1s-.85 3.15-2.25 3.15S9.75 17 9.75 15.1S10.6 12 12 12m-1.5 5.25l3-4.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hrbw6pe9j {
  width: 18.5px;
  height: 16.75px;
  x: 2.75px;
  y: 4.5px;
  rx: 2.25px;
}

</style>
