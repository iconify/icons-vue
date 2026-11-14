<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b1giyo3pl"/><path class="xej5d9b3r"/><path class="hno6rlq2q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pedestrian-crossing-sign" /></template>
<style>
.b1giyo3pl {
  d: path("M6.875 2.5h10.25A4.375 4.375 0 0 1 21.5 6.875v10.25a4.375 4.375 0 0 1-4.375 4.375H6.875A4.375 4.375 0 0 1 2.5 17.125V6.875A4.375 4.375 0 0 1 6.875 2.5");
}

.hno6rlq2q {
  d: path("m9.5 11.25l2.75-1l2.5 2M7 18.5h3.5m3 0H17");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xej5d9b3r {
  d: path("M11.5 5.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m1 4.25l-1.25 3.75l-2.75 2.25m2.75-2.25L14 15.75");
}

</style>
