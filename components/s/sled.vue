<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="u1srlwbqa"/><path class="c3ali2boy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sled" /></template>
<style>
.c3ali2boy {
  d: path("M6.5 13v5.25m8-5.25v5.25m-11.75 0H17A3.25 3.25 0 0 0 20.25 15m-2.5-3.75c2 0 3.5-1.5 3.5-3.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.u1srlwbqa {
  width: 14.5px;
  height: 3.5px;
  x: 3.25px;
  y: 9.5px;
  rx: 1.25px;
}

</style>
