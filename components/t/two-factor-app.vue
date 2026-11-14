<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f5m272btp"/><path class="rniygib0q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:two-factor-app" /></template>
<style>
.f5m272btp {
  d: path("M9.5 2h5A3.5 3.5 0 0 1 18 5.5v13a3.5 3.5 0 0 1-3.5 3.5h-5A3.5 3.5 0 0 1 6 18.5v-13A3.5 3.5 0 0 1 9.5 2m1 2.75h3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rniygib0q {
  d: path("M10.5 11.5h3a1.75 1.75 0 0 1 1.75 1.75v2A1.75 1.75 0 0 1 13.5 17h-3a1.75 1.75 0 0 1-1.75-1.75v-2a1.75 1.75 0 0 1 1.75-1.75m-.25 0v-2a1.75 1.75 0 0 1 3.5 0v2");
}

</style>
