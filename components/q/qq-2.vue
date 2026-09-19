<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d11aoebpk"/><path class="axbi5cb5o"/><path class="e-3mtob9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:qq-2" /></template>
<style>
.axbi5cb5o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.609 34.548A21.503 21.503 0 1 0 23.87 45.5");
}

.d11aoebpk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.791 45.5a5.839 5.839 0 0 0 0-11.678c-.047 0-.092.013-.14.015a6.842 6.842 0 0 0-13.656-.303A6.074 6.074 0 1 0 24.531 45.5Z");
}

.e-3mtob9h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.66 27.51a11.344 11.344 0 1 0-14.163 7.323");
}

</style>
