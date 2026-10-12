<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="dcdfcabho"/><path class="u5ja4pb9f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:vaccine-vial-check" /></template>
<style>
.dcdfcabho {
  width: 6.5px;
  height: 3.5px;
  x: 8.75px;
  y: 2.75px;
  rx: 1px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.u5ja4pb9f {
  d: path("M10 6.25h4v2c1.75.5 2.75 1.75 2.75 3.5v7.5a2 2 0 0 1-2 2h-5.5a2 2 0 0 1-2-2v-7.5c0-1.75 1-3 2.75-3.5ZM7.25 13.5h9.5m-9.5 4h9.5");
}

</style>
