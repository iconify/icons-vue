<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="rhnshm4xa"/><path class="zu1m7xofq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:zero-day-sharp" /></template>
<style>
.rhnshm4xa {
  d: path("M2.75 4.5h18.5v16.75H2.75zM8 2.75v3.5m8-3.5v3.5M2.75 9.5h18.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zu1m7xofq {
  d: path("M12 12c1.4 0 2.25 1.2 2.25 3.1s-.85 3.15-2.25 3.15S9.75 17 9.75 15.1S10.6 12 12 12Zm-1.5 5.25l3-4.25");
}

</style>
