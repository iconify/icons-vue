<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y7t12oqch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:quicktiles" /></template>
<style>
.y7t12oqch {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7 7h17v17H7zm17 0h17v17H24zM7 24h17v17H7zm19.8 2.8h17v17h-17z");
}

</style>
