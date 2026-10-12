<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="q4wmtq_tw"/><path class="hdojlgbgy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:shredder" /></template>
<style>
.hdojlgbgy {
  d: path("M6 12.25h12M6.75 8.75v-5a1 1 0 0 1 1-1h8.5a1 1 0 0 1 1 1v5m-10.5 7v5.5m3.5-5.5v3.75m3.5-3.75v5.5m3.5-5.5v3.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q4wmtq_tw {
  width: 18.5px;
  height: 7px;
  x: 2.75px;
  y: 8.75px;
  rx: 2px;
}

</style>
