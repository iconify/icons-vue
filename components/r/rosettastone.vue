<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q1y4nccra"/><path class="g70owgbqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:rosettastone" /></template>
<style>
.g70owgbqg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.642 26.931a34.134 34.134 0 0 0-25.284 6.5V23.196s13.855-6.787 25.284-4.766Zm-25.284-4.884v12.534");
}

.q1y4nccra {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.358 22.047a34.448 34.448 0 0 1 24.33-6.632l-3.553-8.29a3.841 3.841 0 0 0-3.01-2.292l-2.171-.298a3.842 3.842 0 0 0-3.06.923l-11.233 9.887a3.841 3.841 0 0 0-1.303 2.884Zm0 12.534s13.855-6.787 25.284-4.766v2.502a3.841 3.841 0 0 1-.776 2.314l-5.542 7.342a3.842 3.842 0 0 1-3.066 1.527H17.07a3.841 3.841 0 0 1-2.758-1.167l-1.87-1.93a3.842 3.842 0 0 1-1.084-2.674Z");
}

</style>
