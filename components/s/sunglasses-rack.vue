<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lkh7r6p7x"/><path class="nfuhxhbyp"/><path class="o5o7gnbds"/><path class="lhu78bc9h"/><path class="pcfk-ybpn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sunglasses-rack" /></template>
<style>
.lhu78bc9h {
  fill: currentColor;
  d: path("M9 13.75h4.75v1.5c0 1.5-1 2.25-2.25 2.25h-.25C10 17.5 9 16.75 9 15.25Zm7.25 0H21v1.5c0 1.5-1 2.25-2.25 2.25h-.25c-1.25 0-2.25-.75-2.25-2.25Z");
}

.lkh7r6p7x {
  d: path("M5 2.5v17m-2.5 2h5M5 3.5h10");
}

.nfuhxhbyp {
  fill: currentColor;
  d: path("M9 5.25h4.75v1.5c0 1.5-1 2.25-2.25 2.25h-.25C10 9 9 8.25 9 6.75Zm7.25 0H21v1.5C21 8.25 20 9 18.75 9h-.25c-1.25 0-2.25-.75-2.25-2.25Z");
}

.o5o7gnbds {
  d: path("M13.75 5.75c.75-1 1.75-1 2.5 0M5 12h10");
}

.pcfk-ybpn {
  d: path("M13.75 14.25c.75-1 1.75-1 2.5 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
