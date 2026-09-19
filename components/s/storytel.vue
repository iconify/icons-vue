<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g4bcl7sfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:storytel" /></template>
<style>
.g4bcl7sfw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.67 43.5c4.47-5.72 32.81-4.74 32.81-22.5c0-12.28-9.7-16.5-16.48-16.5S6.52 10.42 6.52 26.42c0 12.43 2.15 17.08 2.15 17.08");
}

</style>
