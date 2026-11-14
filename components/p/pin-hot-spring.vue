<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a9c-2mb0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pin-hot-spring" /></template>
<style>
.a9c-2mb0c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 15.5q2.375-1.5 4.75 0t4.75 0t4.75 0t4.75 0C21 18.75 17 20 12 20s-9-1.25-9.5-4.5Zm5-12q-1.5 2 0 4t0 4m4.5-8q-1.5 2 0 4t0 4m4.5-8q-1.5 2 0 4t0 4");
}

</style>
