<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ay4iwfw_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:radiator-sharp" /></template>
<style>
.ay4iwfw_t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 3.75h3V19.5h-3zm5.5 0h3V19.5h-3zm5.5 0h3V19.5h-3zM6.75 7h2.5m3 0h2.5m-8 9h2.5m3 0h2.5m3 0h2.5m0-1.75v3.5m-15 1.75v1.75m11-1.75v1.75");
}

</style>
