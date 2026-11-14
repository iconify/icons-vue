<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rsvozybmm"/><path class="cg57-2wpz"/><path class="us8_ccnut"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:scroll-depth" /></template>
<style>
.cg57-2wpz {
  fill: currentColor;
  d: path("M17.125 14za.875.875 0 0 1 .875.875v3.25a.875.875 0 0 1-.875.875a.875.875 0 0 1-.875-.875v-3.25a.875.875 0 0 1 .875-.875");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rsvozybmm {
  d: path("M7.875 2.5h8.25A4.375 4.375 0 0 1 20.5 6.875v10.25a4.375 4.375 0 0 1-4.375 4.375h-8.25A4.375 4.375 0 0 1 3.5 17.125V6.875A4.375 4.375 0 0 1 7.875 2.5M3.5 7h17m-14-2.25h.01m2.74 0h.01");
}

.us8_ccnut {
  d: path("M10 10v7.5m-2.75-2.75L10 17.5l2.75-2.75");
}

</style>
