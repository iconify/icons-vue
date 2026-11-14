<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a8v1kgbhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:patient-pickup" /></template>
<style>
.a8v1kgbhx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 8.5h15l-1 13h-13Zm8 0v-3H17v3m-5-6h5.5v3H12Zm-7.25 9h14.5m-7.25 3v4m-2-2h4");
}

</style>
