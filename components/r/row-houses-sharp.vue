<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="vlhrenbwv"/><path class="yl5a8dzza"/><path class="ij6kxnaih"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:row-houses-sharp" /></template>
<style>
.ij6kxnaih {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.25 21.25v-3.5h1.5v3.5");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.vlhrenbwv {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 20.65V10l.38-.46l2.32-2.83l.38-.46l.38.46l2.33 2.83l.38.46l.38-.46l2.32-2.83l.38-.46l.38.46l2.32 2.83l.38.46l.38-.46l2.33-2.83l.38-.46l.38.46l2.32 2.83l.38.46v11.25H2.75zM8.92 10v11.25M15.08 10v11.25");
}

.yl5a8dzza {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5.83 13.5h.01m6.16-1h.01m6.16 1h.01");
}

</style>
