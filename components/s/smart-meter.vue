<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="u6xfwmbeg"/><path class="i-w9lbcqz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:smart-meter" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i-w9lbcqz {
  d: path("M8.25 13h7.5m-7.5 4h3M8 4.75a5.5 5.5 0 0 1 8 0m-5.75 2a2.5 2.5 0 0 1 3.5 0");
}

.u6xfwmbeg {
  width: 15px;
  height: 12.75px;
  x: 4.5px;
  y: 8.5px;
  rx: 3px;
}

</style>
