<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="r7hcpl4dh"/><path class="vq6att4ax"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:savings-jar" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r7hcpl4dh {
  width: 10px;
  height: 2.5px;
  x: 7px;
  y: 3.25px;
  rx: 1px;
}

.vq6att4ax {
  d: path("M7 8.75h10a1 1 0 0 1 1 1V18a3 3 0 0 1-3 3H9a3 3 0 0 1-3-3V9.75a1 1 0 0 1 1-1M10 13h4");
}

</style>
