<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="djjiqhvra"/><path class="o1k4vybtm"/><path class="ehwg0pb9q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:table-freeze" /></template>
<style>
.djjiqhvra {
  d: path("M6 3.5h12A3.5 3.5 0 0 1 21.5 7v10a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 17V7A3.5 3.5 0 0 1 6 3.5");
}

.ehwg0pb9q {
  d: path("M8.75 10v10.5m6.5-10.5v10.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o1k4vybtm {
  fill: currentColor;
  d: path("M3.375 8.25h17.25a.875.875 0 0 1 .875.875a.875.875 0 0 1-.875.875H3.375a.875.875 0 0 1-.875-.875a.875.875 0 0 1 .875-.875");
}

</style>
