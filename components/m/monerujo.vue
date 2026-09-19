<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="csw6h3bco"/><circle class="o7ga-fdrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:monerujo" /></template>
<style>
.csw6h3bco {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.65 44a7.47 7.47 0 0 0 7.49-7.75V19.74c0-3.16-3.94-6.93-7.88-7s-7.88 3.73-7.88 7.13c0-3.36-3.75-7.21-7.58-7.28c-4-.09-8.08 3.37-8.08 7.14v15.7m15.66.01v-15.7M7.72 12.69v7");
}

.o7ga-fdrb {
  cx: 39.13px;
  cy: 6.48px;
  r: 1.54px;
  fill: none;
  stroke: currentColor;
  stroke-miterlimit: 10;
}

</style>
