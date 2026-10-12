<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="ybnbbsg4m"/><path class="zpjpgybup"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sales-funnel" /></template>
<style>
.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ybnbbsg4m {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.5 3.25h.01m4.49 0h.01m4.49 0h.01");
}

.zpjpgybup {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 6.75h15.5q1 0 .35.76l-5.2 5.98q-.65.76-.65 1.76v4.5q0 1-.89.55l-2.72-1.35q-.89-.45-.89-1.45v-2.25q0-1-.65-1.76L3.9 7.51q-.65-.76.35-.76m2.5 4h10.5");
}

</style>
