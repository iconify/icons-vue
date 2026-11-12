<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="kruqtab-m"/><path class="x-1lf64uh"/><path class="ros5bvrws"/><path class="j6-r-u5ao"/><path class="mttyngb9y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:scanner-2-broken" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j6-r-u5ao {
  d: path("M14 22C17.7712 22 19.6569 22 20.8284 20.8284C21.4816 20.1752 21.7706 19.3001 21.8985 18M22 14C22 14.3492 22 14.6822 21.9991 15");
}

.kruqtab-m {
  d: path("M6 13C6 13 7.8 11 12 11C16.2 11 18 13 18 13");
}

.mttyngb9y {
  d: path("M10 2C6.22876 2 4.34315 2 3.17157 3.17157C2.51839 3.82476 2.22938 4.69989 2.10149 6M2 10C2 9.65081 2 9.31779 2.00093 9");
}

.ros5bvrws {
  d: path("M14 2C17.7712 2 19.6569 2 20.8284 3.17157C22 4.34315 22 6.22876 22 10");
}

.x-1lf64uh {
  d: path("M10 22C6.22876 22 4.34315 22 3.17157 20.8284C2 19.6569 2 17.7712 2 14");
}

</style>
