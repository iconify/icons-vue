<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mx3kej69o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tawakkalna-services" /></template>
<style>
.mx3kej69o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5h29c2.216 0 4 1.784 4 4v29c0 2.215-1.784 4-4 4h-29c-2.216 0-4-1.785-4-4v-29c0-2.217 1.784-4 4-4m23.448 9.552a8.92 8.92 0 1 1-17.84 0a8.92 8.92 0 0 1 17.84 0M5.5 24.028h19.141c9.287 0 17.125-8.446 17.235-16.68M5.5 24.028c11.802.006 18.648 8.947 18.468 18.473");
}

</style>
