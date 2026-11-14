<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o_f3p2b-h"/><path class="ybexw231r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mine-headquarters" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o_f3p2b-h {
  d: path("M5.5 7h10A1.5 1.5 0 0 1 17 8.5v11a1.5 1.5 0 0 1-1.5 1.5h-10A1.5 1.5 0 0 1 4 19.5v-11A1.5 1.5 0 0 1 5.5 7m-3 0h16M4 14.75h13M14.5 7V2m1.631.634l.619.241a.939.939 0 0 1 0 1.75l-.619.241A1.197 1.197 0 0 1 14.5 3.75a1.197 1.197 0 0 1 1.631-1.116M2 21h20");
}

.ybexw231r {
  d: path("M7.875 9.75zA1.125 1.125 0 0 1 9 10.875A1.125 1.125 0 0 1 7.875 12a1.125 1.125 0 0 1-1.125-1.125A1.125 1.125 0 0 1 7.875 9.75m5.25 0za1.125 1.125 0 0 1 1.125 1.125A1.125 1.125 0 0 1 13.125 12A1.125 1.125 0 0 1 12 10.875a1.125 1.125 0 0 1 1.125-1.125m-5.25 7.75zA1.125 1.125 0 0 1 9 18.625a1.125 1.125 0 0 1-1.125 1.125a1.125 1.125 0 0 1-1.125-1.125A1.125 1.125 0 0 1 7.875 17.5m5.25 0za1.125 1.125 0 0 1 1.125 1.125v1.25A1.125 1.125 0 0 1 13.125 21A1.125 1.125 0 0 1 12 19.875v-1.25a1.125 1.125 0 0 1 1.125-1.125");
}

</style>
