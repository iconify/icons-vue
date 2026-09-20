<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oze4upblc"/><path class="acyg6nb1v"/><path class="idhymedkk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:viewpoint-outline-thin" /></template>
<style>
.acyg6nb1v {
  d: path("M10 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.idhymedkk {
  d: path("m2 20 6 -6 3 3 5 -5 5 5");
}

.oze4upblc {
  d: path("M6.36 5.95a6 6 0 0 1 11.28 0");
}

</style>
