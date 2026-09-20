<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fyvf420mr"/><path class="c74kujgny"/><path class="quidtccfi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:stew-outline-thin" /></template>
<style>
.c74kujgny {
  d: path("m14 13 5 -5");
}

.fyvf420mr {
  d: path("M4 11h16c0 5 -4 9 -8 9s-8 -4 -8 -9");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.quidtccfi {
  d: path("M9 9c2 -2 0 -4 2 -6");
}

</style>
