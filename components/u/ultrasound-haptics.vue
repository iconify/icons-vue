<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="db2o33blv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ultrasound-haptics" /></template>
<style>
.db2o33blv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 21.5c-1-1.5-1.75-2.5-2.75-3.75l-2-2.5c-.5-.75.5-1.75 1.5-1L7.5 15.5v-2.75a1.25 1.25 0 0 1 2.5 0a1.25 1.25 0 0 1 2.5 0a1.25 1.25 0 0 1 2.5 0a1.25 1.25 0 0 1 2.5 0v5.75c0 1.75-1 3-2.5 3Zm.5-12q2.5-2 5 0M8.5 6.75q4-2 8 0M7 4q5.5-2 11 0");
}

</style>
