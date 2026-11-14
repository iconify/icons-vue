<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ek2pqwf_t"/><path class="ey0_9nb7e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sand-quarry" /></template>
<style>
.ek2pqwf_t {
  d: path("M2.5 21C4 15.5 7 10.5 10 10.5c1.25 0 2 1.25 2.5 2.75m5 1c1.5 1.75 3 4.25 4 6.75m-19 0h19M17 2.25l3.75 1.5M19 3l-3.25 9");
}

.ey0_9nb7e {
  d: path("M13.25 11L18 12.75L16.75 16l-3.25 2l-1.5-3.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
