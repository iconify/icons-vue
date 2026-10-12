<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="m2v_tdb4n"/><path class="jjj1etb8e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:panic-button" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jjj1etb8e {
  d: path("M6 15.25a6 6 0 0 1 12 0Zm6-12.5v3M5.5 5l1.75 1.75M18.5 5l-1.75 1.75");
}

.m2v_tdb4n {
  width: 18.5px;
  height: 6px;
  x: 2.75px;
  y: 15.25px;
  rx: 2px;
}

</style>
