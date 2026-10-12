<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="zmib2rbfy"/><path class="kfrp_y4xt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:rolling-pin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kfrp_y4xt {
  d: path("M9.75 8v8m4.5-8v8m-11.5-4h3.5m11.5 0h3.5");
}

.zmib2rbfy {
  width: 11.5px;
  height: 8px;
  x: 6.25px;
  y: 8px;
  rx: 3px;
}

</style>
