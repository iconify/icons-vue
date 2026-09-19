<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="ghx78abww"/><path class="uz6igib9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mind-cafe" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ghx78abww {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.972 28.012a15.5 15.5 0 0 1-16.995 11.356A15.5 15.5 0 0 1 8.5 24.001A15.5 15.5 0 0 1 21.977 8.634A15.5 15.5 0 0 1 38.972 19.99");
}

.uz6igib9t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.5 23.5c0-3.866 3.358-7 7.5-7s7.5 3.134 7.5 7c0 4.519-5.858 8-10 8c.481-.834.5-1.714.5-1.714c-3.198-.687-5.5-3.049-5.5-6.286");
}

</style>
