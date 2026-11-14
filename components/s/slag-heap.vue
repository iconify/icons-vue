<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w45593mwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:slag-heap" /></template>
<style>
.w45593mwh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2 20c1-4 3-7 5.5-7.5C8.5 9 10 7 12.5 7s4 2.5 4.5 5c2.5 1 4 4 5 8Zm10-8.5h.01m2.49 4h.01M9.5 16h.01M7 17.5h.01");
}

</style>
