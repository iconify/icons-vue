<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="s650lebpm"/><path class="vmjzn84ep"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:plastic-recycling-bin" /></template>
<style>
.s650lebpm {
  d: path("M2.5 7.5h19M4 7.5v11a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2v-11m-13.5 0c1-5.5 10-5.5 11 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vmjzn84ep {
  d: path("m10.5 12.5l1.5-2.25l1.5 2.25m-4.75 3l-1.5 2.25h3.25m3 0h3.25l-1.5-2.25");
}

</style>
