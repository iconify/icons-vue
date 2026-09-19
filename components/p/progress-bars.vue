<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hhfqqhbaq"/><path class="o8nzkubqz"/><path class="i9clfwm2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:progress-bars" /></template>
<style>
.hhfqqhbaq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.701 36.15V22.51m0-4.999V11.85h8.144c4.996 0 7.247 4.05 7.754 5.632m.012 5.028c-.525 1.683-2.832 5.662-7.766 5.662H16.7");
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.o8nzkubqz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.964 17.511h24.073v4.999H11.964zm18.389 0v5");
}

</style>
