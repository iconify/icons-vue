<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bepl9gbwp"/><path class="w3fsooo5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tfl-drive" /></template>
<style>
.bepl9gbwp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 21h39v6h-39zm4.294-.006A15.5 15.5 0 0 1 24 8.5a15.5 15.5 0 0 1 15.207 12.499m-.001 6.007A15.5 15.5 0 0 1 24 39.5A15.5 15.5 0 0 1 8.794 27.006");
}

.w3fsooo5b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.988 20.993A9.5 9.5 0 0 1 24 14.5a9.5 9.5 0 0 1 9.013 6.499m-.001 6.008A9.5 9.5 0 0 1 24 33.501a9.5 9.5 0 0 1-9.011-6.494M6.45 24h5.85m3.9 0h5.85m3.9 0h5.85m3.9 0h5.85M8.793 21l7.064-1.893M39.207 21l-7.064-1.893M8.793 27l7.064 1.893M39.207 27l-7.064 1.893");
}

</style>
