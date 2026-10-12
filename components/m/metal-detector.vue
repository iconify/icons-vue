<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="ogzr66jsm"/><path class="m8mm6uv_e"/><rect class="z4n3wg3rl"/><path class="pucpqccvw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:metal-detector" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m8mm6uv_e {
  d: path("M10 7.5a2 2 0 0 1 4 0V8a2 2 0 0 1-4 0Z");
}

.ogzr66jsm {
  width: 9.5px;
  height: 10.5px;
  x: 7.25px;
  y: 2.75px;
  rx: 4.75px;
}

.pucpqccvw {
  d: path("M19.75 5.25a5 5 0 0 1 0 5.5m-15.5-5.5a5 5 0 0 0 0 5.5");
}

.z4n3wg3rl {
  width: 4px;
  height: 8px;
  x: 10px;
  y: 13.25px;
  rx: 1.5px;
}

</style>
