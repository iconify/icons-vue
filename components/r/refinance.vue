<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gnkbr4bln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:refinance" /></template>
<style>
.gnkbr4bln {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 7.5L9 3l6 4.5m-12 0h12m-12.5 2h13M2.5 20h8.6M4.5 9.5V18M9 9.5V18m4.5-8.5v3.4m1 2.85h6.75M19.5 14l1.75 1.75l-1.75 1.75m2 2.75h-6.75m1.75-1.75l-1.75 1.75L16.5 22");
}

</style>
