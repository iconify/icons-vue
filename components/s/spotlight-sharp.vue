<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yo1stlq5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:spotlight-sharp" /></template>
<style>
.yo1stlq5r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6.87 11.31l3.83-3.45l.74-.67l.5.87l2.25 3.88l.5.87l-.95.31l-4.91 1.59l-.95.31l-.5-.87l-.75-1.3l-.5-.87zm2.28-2.07l2.62 4.52M8 15v5m4-6.3V20m-7 0h8m1.16-14.1L17 3.07M15.66 8.5l3.46-2m-1.96 4.6L21 10.06");
}

</style>
