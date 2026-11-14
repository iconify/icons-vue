<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="eqdv2oblj"/><path class="osdb6_bhl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:neuro-rehab" /></template>
<style>
.eqdv2oblj {
  d: path("M16.492 12.484c-.522.753-1.412 1.17-2.492 1.016c-.75 1.25-2.75 1.5-4 .75c-1.25.75-3.25.5-4-.75c-1.75.25-3-1.25-2.75-2.75c-1-1-1-3 .25-3.75c0-1.5 1.25-2.25 2.5-2c.5-1.5 2.25-2.25 4-1.75c1-1 3-.75 4 .5c1.75 0 3 1.25 2.75 3c1.25 1 1.25 3 .25 4q0 .374-.074.714M12.25 14.75l.304 1.673");
}

.osdb6_bhl {
  d: path("M4.25 10.5c2.25-1 4.75.25 7-1.25M10.5 3c-.5 1.75.5 3 0 4.5m3 4c.75-.75 2-.5 2.5-1.5m-1.75 11.75v-2.5h2.5v-2.5h2.5v-2.5h2.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
