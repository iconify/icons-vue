<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x1_n4d9qq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:outdoor-dining-set" /></template>
<style>
.x1_n4d9qq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 9.5c2-5 5.5-7 9-7s7 2 9 7Zm9 0V21m-7-5.5h14m-11.5 0L6 21m10.5-5.5L18 21");
}

</style>
