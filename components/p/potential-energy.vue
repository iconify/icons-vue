<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jd7wqibwu"/><path class="yz5ajov4h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:potential-energy" /></template>
<style>
.jd7wqibwu {
  d: path("M2.5 21h19m-19-10.5H11V21");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yz5ajov4h {
  d: path("M4.5 7.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm11.5 3V21m-2.25-8.25L16 10.5l2.25 2.25");
}

</style>
