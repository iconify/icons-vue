<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kbcmx-b7t"/><path class="zf1_xzbur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mymaxfitness" /></template>
<style>
.kbcmx-b7t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m25.604 31.639l9.639 6.8l-4.974-11.507");
}

.zf1_xzbur {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m25.604 31.639l4.348-4.386L42.5 14.596l-17.727 6.2L5.5 9.561z");
}

</style>
