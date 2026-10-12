<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zciph_ijp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sun-rain-cloud-sharp" /></template>
<style>
.zciph_ijp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.21 13.98a4.5 4.5 0 1 1 5.65-6.06m-8.53 6.25l-.53.53M3.5 9.75h-.75m2.58-4.42L4.8 4.8m4.95-1.3v-.75m4.42 2.58l.53-.53m-1.5 12.45a2.22 2.22 0 0 1-.31-4.42a3.19 3.19 0 0 1 5.91-.76a2.49 2.49 0 0 1-.33 5.18Zm-3.7-.5l-.75 2.5m6 0l-.5 2m4-2l-.5 2");
}

</style>
