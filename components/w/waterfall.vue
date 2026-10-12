<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="bopw041cc"/><path class="jve4hdceg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:waterfall" /></template>
<style>
.bopw041cc {
  width: 18.5px;
  height: 4.5px;
  x: 2.75px;
  y: 2.75px;
  rx: 1.25px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jve4hdceg {
  d: path("M8 10v6m4-6v8m4-8v6M2.75 21.25c1.54 0 1.54-1.25 3.08-1.25s1.54 1.25 3.08 1.25S10.45 20 11.99 20s1.54 1.25 3.08 1.25S16.61 20 18.15 20s1.54 1.25 3.08 1.25");
}

</style>
