<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="up8eomb_k"/><path class="kfmxlhb_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:passwordstore" /></template>
<style>
.kfmxlhb_i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.521 17.5h3.317a4 4 0 0 1 3.953 4.608l-2.77 18a4 4 0 0 1-3.953 3.392H12.932a4 4 0 0 1-3.954-3.392l-2.769-18a4 4 0 0 1 3.953-4.608h19.36m-3.65 13.675l3.903-3.503");
}

.up8eomb_k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35 25.677a3 3 0 1 1-3-3.002a3.013 3.013 0 0 1 3 3.002m-8.354 7.498a3 3 0 1 1-3-3.002a3.013 3.013 0 0 1 3 3.002M35 37.077a3 3 0 1 1-3-3.002a3.013 3.013 0 0 1 3 3.002m-3-14.402V12.286A7.786 7.786 0 0 0 24.214 4.5h-.428A7.786 7.786 0 0 0 16 12.286V17.5m16 16.575v-5.4");
}

</style>
