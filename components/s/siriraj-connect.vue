<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r-06qwpsw"/><path class="whd32gb0l"/><path class="feb_bytol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:siriraj-connect" /></template>
<style>
.feb_bytol {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.04 4.5c-6.318 7.186 5.2 10.785-3.413 16.697");
}

.r-06qwpsw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.296 30.124c-8.176.244-6.896 8.585-4.529 10.807c2.367 2.22 7.39 3.94 11.36 1.033c2.976-2.179 3.282-6.545 1.903-10.787s-2.114-6.87.41-8.119c1.726-.853 3.964 1.56.84 3.566m6.434-10.47c1.414 1.94 1.874 4.996.398 9.403");
}

.whd32gb0l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.116 40.961c6.02-2.267 2.32-8.395.981-12.964c-1.337-4.569-3.15-9.902 1.915-13.197c1.727-1.123 4.102-1.601 6.284-1.233");
}

</style>
