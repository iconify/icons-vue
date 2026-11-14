<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uq83cdq-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tsunami-wave" /></template>
<style>
.uq83cdq-c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 20c3.5 0 5.5-5 6-9c1-7 7.5-8.5 11-5.5c2 2 1 5.5-2 5.5c-2 0-2.5-2-1.5-3M2.5 20h12m0 0l7-5");
}

</style>
