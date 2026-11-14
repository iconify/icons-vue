<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k5h-jtkjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:row-cover" /></template>
<style>
.k5h-jtkjn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 19.5c0-17.5 19-17.5 19 0M2 19.5h20m-13.5 0v-3m0 0l-1.75-1.75M8.5 16.5l1.75-1.75m5.25 4.75v-3m0 0l-1.75-1.75m1.75 1.75l1.75-1.75");
}

</style>
