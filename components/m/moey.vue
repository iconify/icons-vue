<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="d6iqp2bjo"/><path class="df-kvnbym"/><circle class="tu7u57s8z"/><path class="dtviotcjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:moey" /></template>
<style>
.d6iqp2bjo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.316 21.181a3.682 3.682 0 1 1 7.365 0v6.076m-7.365-9.758v9.758");
}

.df-kvnbym {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.68 21.181a3.682 3.682 0 1 1 7.365 0v6.076");
}

.dtviotcjo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.934 17.222v8.95");
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.tu7u57s8z {
  cx: 32.934px;
  cy: 30.028px;
  r: 0.75px;
  fill: currentColor;
}

</style>
