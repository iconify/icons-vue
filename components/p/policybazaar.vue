<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="y_3lkbb8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:policybazaar" /></template>
<style>
.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.y_3lkbb8q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.215 23.142a2.46 2.46 0 0 1 2.453-2.453h0a2.46 2.46 0 0 1 2.452 2.453v1.594a2.46 2.46 0 0 1-2.452 2.453h0a2.46 2.46 0 0 1-2.453-2.453m0 2.575V17.5m-7.335 7.359a2.46 2.46 0 0 0 2.452 2.452h0a2.46 2.46 0 0 0 2.453-2.453v-1.594a2.46 2.46 0 0 0-2.453-2.453h0a2.46 2.46 0 0 0-2.452 2.453m0-2.575V30.5");
}

</style>
