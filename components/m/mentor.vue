<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nbc18yb1o"/><path class="orng1obik"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mentor" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nbc18yb1o {
  d: path("m6 4.75l1.717-.859a1.75 1.75 0 0 1 1.566 0L11 4.75a1.398 1.398 0 0 1 0 2.5l-1.717.859a1.75 1.75 0 0 1-1.566 0L6 7.25a1.398 1.398 0 0 1 0-2.5");
}

.orng1obik {
  d: path("M5.5 7.5V10a3 3 0 0 0 6 0V7.5m-9 14C2.5 18 5 16 8.5 16s6 2 6 5.5m2-8.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m.75 8.5c0-2.25.75-3.5 2-3.5s2.25 1.25 2.25 3.5");
}

</style>
