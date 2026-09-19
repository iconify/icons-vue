<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m2138o3og"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tachij2k" /></template>
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

.m2138o3og {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.757 34.53h26.486M12.139 14.729h23.722M27.243 34.53c4.68-6.901 6.357-9.378 5.581-16.68m-17.842 0c-.856 6.605 3.044 12.531 4.345 14.603m6.779-17.724l1.607-3.284l-2.472.721L24 9.22l-1.241 2.946l-2.472-.721l1.607 3.284");
}

</style>
