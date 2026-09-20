<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="od9me8bls"/><path class="unoof1b_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:miraiya-shoten" /></template>
<style>
.od9me8bls {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 39.5V18.946c2.696-1.576 6.15-2.446 9.75-2.446c3.59 0 7.057.865 9.75 2.434c2.697-1.576 6.172-2.447 9.772-2.447s7.032.87 9.728 2.447V39.5M24 18.934V39.5");
}

.unoof1b_l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.75 16.511V8.5l4.375 2l4.375-2v9.448");
}

</style>
