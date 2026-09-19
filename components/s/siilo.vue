<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ijuej06ch"/><circle class="z1qn5cbew"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:siilo" /></template>
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

.ijuej06ch {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.812 32.73a7.07 7.07 0 0 0 5.837 2.534h3.502a5.635 5.635 0 1 0 0-11.264h-3.794a5.754 5.754 0 0 1-5.837-5.632a5.754 5.754 0 0 1 5.837-5.632h3.503c2.627 0 4.378.564 5.837 2.535");
}

.z1qn5cbew {
  cx: 35.235px;
  cy: 33.018px;
  r: 2.246px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
