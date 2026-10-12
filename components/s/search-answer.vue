<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="svf90nw7c"/><path class="jfinfmbaz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:search-answer" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jfinfmbaz {
  d: path("M6.25 6h7m4-2.25Q17.52 5.73 19.5 6q-1.98.27-2.25 2.25Q16.98 6.27 15 6q1.98-.27 2.25-2.25m-14.5 9.5h18.5m-18.5 4h18.5m-18.5 4h10");
}

.svf90nw7c {
  width: 18.5px;
  height: 6.5px;
  x: 2.75px;
  y: 2.75px;
  rx: 3.25px;
}

</style>
