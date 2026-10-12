<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="o_nrn_b7n"/><path class="ydmnjbhla"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mirror" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o_nrn_b7n {
  width: 12.5px;
  height: 15.5px;
  x: 5.75px;
  y: 2.75px;
  rx: 6.25px;
}

.ydmnjbhla {
  d: path("m9.25 9.25l3-3m-2.5 6.5l5-5M12 18.25v3m-3.5 0h7");
}

</style>
