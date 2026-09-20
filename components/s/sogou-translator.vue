<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gn82t4bsg"/><path class="zlrfalb2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sogou-translator" /></template>
<style>
.gn82t4bsg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.696 29.027h5.327a3.64 3.64 0 0 0 3.648-3.644v-5.365h2.48c1.222 0 2.296-1.581 1.434-2.48l-3.915-4.082h-5.39a3.574 3.574 0 0 0-3.583 3.58l-.002 5.429l-3.917 4.082c-.862.9.213 2.48 1.433 2.48h2.462");
}

.zlrfalb2t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.696 33.974a3.574 3.574 0 0 0 3.583 3.581h10.995l5.737 5.945l.001-26.464a3.574 3.574 0 0 0-3.582-3.58h-7.76V8.144A3.64 3.64 0 0 0 25.024 4.5H11.635a3.64 3.64 0 0 0-3.647 3.644l.001 26.934l5.84-6.05h5.867z");
}

</style>
