<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l6h0z5boc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:snow-drift" /></template>
<style>
.l6h0z5boc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 19C7 19 9 10 14.5 9c3.5-.5 6.5 1.5 7 4.5c-2-1-4.5-.5-5 1.5m-14 4h19M6 8h.01M11 4.5h.01m6.99 0h.01");
}

</style>
