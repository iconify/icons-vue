<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gqmkvbb9n"/><path class="fx2elr4-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:orange-flex" /></template>
<style>
.fx2elr4-v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.491 29.226a3.494 3.494 0 0 1-6.53-1.73v-2.272a3.494 3.494 0 0 1 6.987 0v1.135h-6.986M9.5 21.73h4.891m-2.82 9.259V19.457a2.446 2.446 0 0 1 2.446-2.445h.952c1.204 0 1.972.356 2.487 1.023v11.204c0 .965.782 1.747 1.747 1.747h.524");
}

.gqmkvbb9n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4m0 16.23l-6.987 9.258m6.987 0l-6.987-9.258");
}

</style>
