<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="s_5bo2bpv"/><path class="czfy7cc8o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tide-pool-sharp" /></template>
<style>
.czfy7cc8o {
  d: path("m12.15 10.82l.76 1.66l.15.31l.35.04l1.81.22l.35.04l-.26.24l-1.34 1.24l-.26.24l.07.34l.36 1.79l.06.34l-.3-.17l-1.59-.89l-.31-.17l-.31.17l-1.59.89l-.3.17l.06-.34l.36-1.79l.07-.34l-.26-.24l-1.34-1.24l-.26-.24l.35-.04l1.81-.22l.35-.04l.15-.31l.76-1.66l.15-.32z");
}

.s_5bo2bpv {
  d: path("M3.88 11.25h0L5 8.5l2.85-.95l.3-.1L11 6.5l2.98.34l.54.07l2.98.34l1.74 2.44l.27.37l1.74 2.44l-.59 2.94l-.07.37l-.59 2.94l-2.83 1.01l-1.34.48L13 21.25l-2.94-.59l-1.62-.32l-2.94-.59l-1.29-2.71l-.17-.33L2.75 14z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
