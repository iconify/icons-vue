<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fjql5r5sl"/><path class="etf-0vb0j"/><path class="i9clfwm2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:wiebetaaldwat" /></template>
<style>
.etf-0vb0j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.64 21.884h2.753a1.64 1.64 0 1 1 0 3.28h-2.752m0-16.353l1.634 6.549m1.635-6.549l-1.635 6.549m1.635-6.549l1.635 6.549m1.635-6.549l-1.635 6.549m-4.904 13.048l1.634 6.548m1.635-6.548l-1.635 6.548m1.635-6.548l1.635 6.548m1.635-6.548l-1.635 6.548M8.821 38.43H39.18");
}

.fjql5r5sl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.641 25.143v-6.538m-.001 0h2.753a1.64 1.64 0 1 1 0 3.28h-2.752");
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

</style>
