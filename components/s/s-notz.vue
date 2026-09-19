<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cll99bgay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:s-notz" /></template>
<style>
.cll99bgay {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39 5H9a4 4 0 0 0-4 4v30a4 4 0 0 0 4 4h23.56V32.56H43V9a4 4 0 0 0-4-4m-6.44 38L43 32.56M10.5 14h27m-27 10h27m-27 10h16.06");
}

</style>
