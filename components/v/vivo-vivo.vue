<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="eyp-3fvso"/><path class="oe8h0tb6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:vivo-vivo" /></template>
<style>
.eyp-3fvso {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.877 12.069c-8.894 0-10.872 12.99 0 23.862c10.858-10.858 8.894-23.862 0-23.862");
}

.oe8h0tb6z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.684 19.056c6.289-6.29 16.873 1.499 16.873 16.873C8.201 35.93.394 25.345 6.684 19.056m34.633 0c-6.29-6.29-16.874 1.499-16.874 16.873c15.356 0 23.163-10.584 16.873-16.873");
}

</style>
