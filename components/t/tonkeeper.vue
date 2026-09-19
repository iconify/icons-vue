<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qig7zd4-j"/><path class="q7g_7nb_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tonkeeper" /></template>
<style>
.q7g_7nb_r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24.053 41.255l-.058-20.948l18.505-7.05m-37 0l18.495 7.05");
}

.qig7zd4-j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m5.5 13.257l18.553 27.998L42.5 13.256l-18.505-6.51z");
}

</style>
