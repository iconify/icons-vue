<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="f7r42znre"/><path class="ay74dgert"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:stock-down" /></template>
<style>
.ay74dgert {
  d: path("m6.75 8.25l3.5 3.5l2.5-2.5l4.5 4.5m-3.75 0h3.75V10");
}

.f7r42znre {
  width: 18.5px;
  height: 18.5px;
  x: 2.75px;
  y: 2.75px;
  rx: 2.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
