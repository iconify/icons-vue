<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xtgdqevzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:user-growth" /></template>
<style>
.xtgdqevzv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2 21c0-1.75.9-2.75 2.25-2.75s2.25 1 2.25 2.75m1.25 0c0-3 1.15-4.75 2.75-4.75S13.25 18 13.25 21m1.25 0c0-4.5 1.5-7.5 3.75-7.5S22 16.5 22 21M2.75 15.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm5.5-3.25a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm7-4.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

</style>
