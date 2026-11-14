<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="csxkp-f3z"/><path class="u57o3obdo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:usb-stick-check" /></template>
<style>
.csxkp-f3z {
  d: path("M10.5 9h3a3.5 3.5 0 0 1 3.5 3.5V18a3.5 3.5 0 0 1-3.5 3.5h-3A3.5 3.5 0 0 1 7 18v-5.5A3.5 3.5 0 0 1 10.5 9m-.25-6.5h3.5a1.75 1.75 0 0 1 1.75 1.75v3A1.75 1.75 0 0 1 13.75 9h-3.5A1.75 1.75 0 0 1 8.5 7.25v-3a1.75 1.75 0 0 1 1.75-1.75m.5 3.25h2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.u57o3obdo {
  d: path("m9.75 15.5l1.75 1.75l3-3.5");
}

</style>
