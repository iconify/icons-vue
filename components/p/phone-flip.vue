<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="g94cbqf4f"/><path class="mi9zcwbpy"/><rect class="j3gq2q7jz"/><path class="zv0tyccbb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:phone-flip" /></template>
<style>
.g94cbqf4f {
  width: 11.5px;
  height: 8px;
  x: 6.25px;
  y: 2.75px;
  rx: 2px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j3gq2q7jz {
  width: 11.5px;
  height: 8px;
  x: 6.25px;
  y: 13.25px;
  rx: 2px;
}

.mi9zcwbpy {
  d: path("M9.25 6.75h5.5");
}

.zv0tyccbb {
  d: path("M9.25 16.25h5.5m-5.5 2.5h5.5");
}

</style>
