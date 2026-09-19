<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p968p_e5b"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:moin-card" /></template>
<style>
.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.p968p_e5b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.75 34.383v-8h1.3a4.01 4.01 0 0 1 4 4h0a4.01 4.01 0 0 1-4 4zm-7.584 0v-8h2.6a2.7 2.7 0 1 1 0 5.4h-2.6m2.79-.006l2.51 2.606m-8.602-2.7h-3.4m4.3 2.7l-2.6-7.999l-2.7 7.999m.9-2.7h3.5m-6.512 0a2.69 2.69 0 0 1-2.678 2.7h-.022a2.69 2.69 0 0 1-2.7-2.677q0 0 0 0v-2.723a2.69 2.69 0 0 1 2.677-2.7h.023a2.606 2.606 0 0 1 2.602 2.61h0l-.002.09h0m14.281-15.267v8m-19.582 0v-8l4 8l4-8v8m14.722 0v-8l5.3 8v-8m-16.88 5.301a2.65 2.65 0 1 0 5.3 0v-2.7a2.69 2.69 0 0 0-2.678-2.7q0 0 0 0h-.022a2.606 2.606 0 0 0-2.602 2.61h0l.002.09z");
}

</style>
