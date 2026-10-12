<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="erih4-u_k"/><path class="szcd0abei"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:radiator-car" /></template>
<style>
.erih4-u_k {
  width: 17px;
  height: 12.75px;
  x: 3.5px;
  y: 5.75px;
  rx: 1.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.szcd0abei {
  d: path("M7.25 8.75v6.75m3.25-6.75v6.75m3.25-6.75v6.75M17 8.75v6.75m-6.5-9.75v-2a1 1 0 0 1 1-1h1a1 1 0 0 1 1 1v2m-7 12.75v2.75m11-2.75v2.75");
}

</style>
