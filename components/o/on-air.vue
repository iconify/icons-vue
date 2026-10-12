<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="r3_1npb-l"/><circle class="m1is5jemp"/><path class="z0qge-b2w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:on-air" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m1is5jemp {
  cx: 7.75px;
  cy: 12px;
  r: 2px;
}

.r3_1npb-l {
  width: 18.5px;
  height: 9px;
  x: 2.75px;
  y: 7.5px;
  rx: 2.5px;
}

.z0qge-b2w {
  d: path("M12.25 12h5.5");
}

</style>
