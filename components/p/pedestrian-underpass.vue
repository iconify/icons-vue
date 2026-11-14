<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tqzx1eb1i"/><path class="vm5dgib_v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pedestrian-underpass" /></template>
<style>
.tqzx1eb1i {
  d: path("M3 21.5v-10c0-5 4-9 9-9s9 4 9 9v10m-19 0h20");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vm5dgib_v {
  d: path("M10.75 7.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0ZM12 11.25l-1 3.5M8.75 18.5L11 14.75l2.5 3.75m-4.25-5.25l2.5-1.5l2.5 1.25");
}

</style>
