<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a6suir50i"/><path class="i5saebbsd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:service-callback" /></template>
<style>
.a6suir50i {
  d: path("M6.75 7c.75 0 1 .5 1.25 1l.75 2.75q0 .75-.75 1.5L6.75 13c1 2 2 3.25 4.25 4.25l.75-1.25q.75-.75 1.5-.75L16 16c.5.25 1 .5 1 1.25v2.5c0 1-.75 1.75-1.75 1.75c-6.75 0-12.75-6-12.75-12.75c0-1 .75-1.75 1.75-1.75Zm6 0a4 4 0 1 1 6 3.464");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i5saebbsd {
  d: path("m16 9.75l2.75.75l.5-2.75");
}

</style>
