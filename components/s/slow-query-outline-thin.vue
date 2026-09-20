<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="llc-u9kbe"/><path class="yjzepunpt"/><path class="f_-gw6caf"/><path class="gh7xyhbdv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:slow-query-outline-thin" /></template>
<style>
.f_-gw6caf {
  d: path("M11 7v4");
}

.gh7xyhbdv {
  d: path("M11 11h3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.llc-u9kbe {
  d: path("M5 11a6 6 0 1 0 12 0 6 6 0 1 0 -12 0");
}

.yjzepunpt {
  d: path("M15.5 15.5 20 20");
}

</style>
