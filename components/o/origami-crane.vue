<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zr5cnvbvh"/><path class="na56vrbiz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:origami-crane" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.na56vrbiz {
  d: path("m9.99 14.06l5.77-10.62q.24-.44.63-.13l1.72 1.38q.39.31.21.78l-3.64 9.56q-.18.47-.67.37l-3.77-.8q-.49-.1-.25-.54");
}

.zr5cnvbvh {
  d: path("m3.04 6.1l1.42-1.95q.29-.4.67-.08l.74.61q.38.32.55.79l3.16 8.56q.17.47.66.57l3.77.8q.49.1.92-.15l5.89-3.5q.43-.25.21.2l-3.56 7.1q-.22.45-.72.45H9q-.5 0-.7-.46L2.95 6.96q-.2-.46.09-.86");
}

</style>
