<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="kxq9ww4ym"/><path class="h67stpbmw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:text-box" /></template>
<style>
.h67stpbmw {
  d: path("M8.25 8.75h7.5m-3.75 0v7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kxq9ww4ym {
  width: 16.5px;
  height: 16.5px;
  x: 3.75px;
  y: 3.75px;
  rx: 2.5px;
}

</style>
