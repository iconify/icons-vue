<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sky13jw6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tilt-sensor" /></template>
<style>
.sky13jw6b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 20.5h18M4.036 8.652l9.97-4.648l2.958 6.344l-9.97 4.648ZM20.5 17.5a8 8 0 0 0-1.25-4.75");
}

</style>
