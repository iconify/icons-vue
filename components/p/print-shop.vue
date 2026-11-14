<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dacsjjblv"/><path class="a2b2djbad"/><path class="v9n0dzinn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:print-shop" /></template>
<style>
.a2b2djbad {
  d: path("M5.25 10.25V21.5h13.5V10.25");
}

.dacsjjblv {
  d: path("m3 8l1.5-5h15L21 8a2.25 2.25 0 0 1-4.5 0A2.25 2.25 0 0 1 12 8a2.25 2.25 0 0 1-4.5 0A2.25 2.25 0 0 1 3 8Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v9n0dzinn {
  d: path("M8 15.25h8v3.5H8Zm2 0V13h4v2.25");
}

</style>
