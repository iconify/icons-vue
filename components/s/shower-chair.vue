<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a1q803bes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:shower-chair" /></template>
<style>
.a1q803bes {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 6.5h18V12H3Zm4.5 2.75h.01m4.49 0h.01m4.49 0h.01M5 12l-1.5 9.5m6-9.5L9 21.5m5.5-9.5l.5 9.5m4-9.5l1.5 9.5");
}

</style>
