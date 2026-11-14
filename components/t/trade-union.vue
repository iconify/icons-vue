<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vepmrxbqr"/><path class="v--4khbeq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:trade-union" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v--4khbeq {
  d: path("M6.5 9.5h3a1.5 1.5 0 0 1 0 3m-1 .5v6.5m7-6.5v6.5");
}

.vepmrxbqr {
  d: path("M10 4.5h4A3.5 3.5 0 0 1 17.5 8v1.5A3.5 3.5 0 0 1 14 13h-4a3.5 3.5 0 0 1-3.5-3.5V8A3.5 3.5 0 0 1 10 4.5m-.75 0v3m2.75-3v3m2.75-3v3");
}

</style>
