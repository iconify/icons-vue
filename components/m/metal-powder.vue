<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cgyhawbyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:metal-powder" /></template>
<style>
.cgyhawbyr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 19h19M4 19c4-2 5-10 8-10s4 8 8 10m-8-4.5h.01M4.5 14h.01m14.99 0h.01M12 4.75h.01");
}

</style>
