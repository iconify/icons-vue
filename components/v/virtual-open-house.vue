<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="q02j1fbyl"/><path class="dhb-3bgbm"/><path class="kuah_lx3n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:virtual-open-house" /></template>
<style>
.dhb-3bgbm {
  d: path("M11 13V5.5h5V13");
}

.kuah_lx3n {
  fill: currentColor;
  d: path("M11 5.5L7.5 7v6H11Z");
}

.q02j1fbyl {
  d: path("M4 3h16v12.5H4ZM2.5 19.5l1.5-4h16l1.5 4Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
