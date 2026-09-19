<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w9dnp2biv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pixelator" /></template>
<style>
.w9dnp2biv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4m-23.75 0v37M24 5.5v37m9.25-37v37m9.25-27.75h-37m37 9.25h-37m37 9.25h-37m4.625-18.5V5.5M5.5 10.125h9.25M28.625 24v-9.25M24 19.375h9.25M19.375 42.5v-9.25m-4.625 4.625H24M37.875 24v-9.25m-4.625 4.625h9.25");
}

</style>
