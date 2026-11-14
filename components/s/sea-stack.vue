<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mc7txkb2x"/><path class="lveo3ccan"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sea-stack" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lveo3ccan {
  d: path("M2.5 17q1.75-1.5 3.5 0h12q1.75 1.5 3.5 0M6 20.5q2-1.5 4 0t4 0t4 0");
}

.mc7txkb2x {
  d: path("m8 17l.75-8l1.5-5h3.25l1.75 4.5L16 17");
}

</style>
