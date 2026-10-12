<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="u7hfq__pz"/><path class="a0ljzhbqy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:toll" /></template>
<style>
.a0ljzhbqy {
  d: path("M6.5 8.25H9v3.5H6.5Zm7 5h7.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.u7hfq__pz {
  width: 8px;
  height: 16.5px;
  x: 3.75px;
  y: 4.75px;
  rx: 2px;
}

</style>
