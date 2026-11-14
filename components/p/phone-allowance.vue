<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="f18_f1p2j"/><path class="uox3-lb0n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:phone-allowance" /></template>
<style>
.f18_f1p2j {
  d: path("M5.5 2.5h13v19h-13Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uox3-lb0n {
  d: path("M8.5 11a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Zm3.5-1v2m-1.5 6.5h3");
}

</style>
