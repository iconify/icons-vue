<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y78td4b7l"/><path class="bq6phz2kf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:xctrack" /></template>
<style>
.bq6phz2kf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.01 27.19c0 11.773-10.809.962-10.809 12.733m27.349-9.058c0-4.858-10.677-5.339-10.677.13v5.427c0 4.245 10.852 4.551 10.852-.831M7.395 24.652L5.5 14.51s22.677-18.868 37 8.02C21.89 4.18 7.394 24.65 7.394 24.65z");
}

.y78td4b7l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.202 27.19c0 11.773 10.809.962 10.809 12.733");
}

</style>
