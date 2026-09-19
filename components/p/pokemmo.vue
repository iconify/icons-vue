<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="nmqno7bjl"/><path class="m-2lcmi-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pokemmo" /></template>
<style>
.m-2lcmi-x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M2.83 27.75C4.6 37.83 13.4 45.49 23.99 45.49s19.39-7.66 21.16-17.74h-8.71c-1.61 5.35-6.58 9.24-12.45 9.24s-10.84-3.89-12.45-9.24zm-.01-7.5C4.59 10.16 13.4 2.49 23.99 2.49s19.4 7.67 21.17 17.76h-8.71c-1.61-5.36-6.58-9.26-12.46-9.26s-10.85 3.9-12.46 9.26z");
}

.nmqno7bjl {
  cx: 23.99px;
  cy: 23.99px;
  r: 8px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
