<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ys-85vbgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:space-probe-sharp" /></template>
<style>
.ys-85vbgg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.21 9.84L17.42 5.4A6.5 3.75-20 0 1 5.21 9.84Zm6.11-2.22l-1.2-3.29m2.48 6.81l-.6 2.61m-2.25 0h4.5v3.75h-4.5zm0 1.75l-7 1.5m11.5-1.5l7 1.5");
}

</style>
