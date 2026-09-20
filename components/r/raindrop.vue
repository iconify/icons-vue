<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dqu-t7q6k"/><path class="e0_f694sv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:raindrop" /></template>
<style>
.dqu-t7q6k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.25 19.855za9.75 9.75 0 0 1 9.75 9.75v9.75h-9.75a9.75 9.75 0 0 1-9.75-9.75a9.75 9.75 0 0 1 9.75-9.75m9.75 19.5h9.75a9.75 9.75 0 0 0 9.75-9.75a9.75 9.75 0 0 0-9.75-9.75a9.75 9.75 0 0 0-9.75 9.75");
}

.e0_f694sv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.995 12.371za12.72 12.72 0 0 1 0 17.989L24 39.354l-8.994-8.994a12.72 12.72 0 0 1 0-17.989a12.72 12.72 0 0 1 17.989 0");
}

</style>
