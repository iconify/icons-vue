<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="gb8powawe"/><path class="rjt4yjb1k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:trapezoid" /></template>
<style>
.gb8powawe {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 5h4.5q2 0 2.7 1.87l3.85 10.26Q21.5 19 19.5 19h-15q-2 0-1.3-1.87L7.05 6.87Q7.75 5 9.75 5");
}

.rjt4yjb1k {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 13h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
