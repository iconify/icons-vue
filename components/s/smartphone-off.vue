<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="rmm1voz9v"/><path class="hgx_7np8d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:smartphone-off" /></template>
<style>
.hgx_7np8d {
  d: path("M10.25 18h3.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rmm1voz9v {
  width: 12.5px;
  height: 18.5px;
  x: 5.75px;
  y: 2.75px;
  rx: 2.5px;
}

</style>
