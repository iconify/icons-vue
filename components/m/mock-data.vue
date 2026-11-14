<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="en58i-pqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mock-data" /></template>
<style>
.en58i-pqt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 5.5a7.5 3 0 1 0 15 0a7.5 3 0 1 0-15 0Zm0 0v3m0 2.75v3m0 2.75v1.5a7.5 3 0 0 0 2.75 2.25m2.75.75h4m2.75-.75a7.5 3 0 0 0 2.75-2.25V17m0-2.75v-3m0-2.75v-3");
}

</style>
