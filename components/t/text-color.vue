<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nw5260bys"/><rect class="gkctxob2o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:text-color" /></template>
<style>
.gkctxob2o {
  width: 17.5px;
  height: 3.5px;
  x: 3.25px;
  y: 17.5px;
  rx: 1.25px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nw5260bys {
  d: path("M6.5 15L12 3.75L17.5 15m-9-4h7");
}

</style>
