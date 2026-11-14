<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o62csxcvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:margarita" /></template>
<style>
.o62csxcvl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 6.5h19c0 4-4.5 6-9.5 6s-9.5-2-9.5-6Zm9.5 6v8m-4 0h8m-.5-14a3 3 0 0 1 6 0");
}

</style>
