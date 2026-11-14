<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sc9ctsbop"/><path class="oxdnk4boz"/><path class="jsjyhei4y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:snacks-aisle" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jsjyhei4y {
  d: path("M10.25 13.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

.oxdnk4boz {
  d: path("m8 9.5l1.25-.75l1.25.75l1.25-.75L13 9.5l1.25-.75l1.25.75c1 2.5 1 5.5 0 8l-1.25.75L13 17.5l-1.25.75l-1.25-.75l-1.25.75L8 17.5C7 15 7 12 8 9.5");
}

.sc9ctsbop {
  d: path("M2.5 2.5h19M7 2.5V7m10-4.5V7M6 7h12a3.5 3.5 0 0 1 3.5 3.5v6A3.5 3.5 0 0 1 18 20H6a3.5 3.5 0 0 1-3.5-3.5v-6A3.5 3.5 0 0 1 6 7");
}

</style>
