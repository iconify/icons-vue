<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="rv385tbng"/><path class="azrz69bot"/><rect class="v0efanbpd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:storage-box" /></template>
<style>
.azrz69bot {
  d: path("M4.25 7.75h15.5v11.5a2 2 0 0 1-2 2H6.25a2 2 0 0 1-2-2Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rv385tbng {
  width: 18.5px;
  height: 3.5px;
  x: 2.75px;
  y: 4.25px;
  rx: 1.25px;
}

.v0efanbpd {
  width: 6px;
  height: 2.5px;
  x: 9px;
  y: 10.75px;
  rx: 1.25px;
}

</style>
