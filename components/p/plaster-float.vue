<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="q172l3b9d"/><rect class="czd57mcxk"/><path class="z06ex2g_z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:plaster-float" /></template>
<style>
.czd57mcxk {
  width: 9px;
  height: 3.5px;
  x: 7.5px;
  y: 8px;
  rx: 1.75px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q172l3b9d {
  width: 18.5px;
  height: 2.25px;
  x: 2.75px;
  y: 14px;
  rx: 1px;
}

.z06ex2g_z {
  d: path("M9.5 11.5V14m5-2.5V14");
}

</style>
