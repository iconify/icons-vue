<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="upddb4dxn"/><path class="teuoewbyq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:story-reel" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.teuoewbyq {
  d: path("M8.5 6.25h2m3 0h2m-4.66 4.88l3.07 1.99q.59.38 0 .76l-3.07 1.99q-.59.38-.59-.32v-4.1q0-.7.59-.32");
}

.upddb4dxn {
  width: 13.5px;
  height: 18.5px;
  x: 5.25px;
  y: 2.75px;
  rx: 2.5px;
}

</style>
