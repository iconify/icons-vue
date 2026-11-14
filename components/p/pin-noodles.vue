<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="i2af6890h"/><path class="nty362flz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pin-noodles" /></template>
<style>
.i2af6890h {
  d: path("M3 11h18c0 5.25-4 9-9 9s-9-3.75-9-9Zm10.5 0l4-8m-1 8L21 4");
}

.nty362flz {
  d: path("M7.5 15.5q2.25-1.5 4.5 0t4.5 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
