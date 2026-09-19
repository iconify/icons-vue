<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q37hhyb5v"/><path class="qcwfcu35p"/><path class="i9clfwm2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:shelly-smart-control" /></template>
<style>
.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.q37hhyb5v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38 24.727v2.437a1.81 1.81 0 0 1-1.804 1.805h0a1.51 1.51 0 0 1-1.263-.542");
}

.qcwfcu35p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38 21.748v2.979a1.81 1.81 0 0 1-1.804 1.805h0a1.81 1.81 0 0 1-1.804-1.805v-2.979m-6.365-2.708v6.318a.852.852 0 0 0 .902.903h.27m2.011-7.221v6.318a.852.852 0 0 0 .901.903h.271m-6.636-.903a1.75 1.75 0 0 1-1.533.903h0a1.81 1.81 0 0 1-1.804-1.805v-1.174a1.81 1.81 0 0 1 1.804-1.805h0a1.81 1.81 0 0 1 1.804 1.805v.632h-3.608m-5.618-4.874v7.221m-.001-2.979a1.81 1.81 0 0 1 1.805-1.805h0a1.81 1.81 0 0 1 1.804 1.805v2.979m-10.309-.812a2.15 2.15 0 0 0 1.804.812h1.083a1.81 1.81 0 0 0 1.804-1.805h0a1.81 1.81 0 0 0-1.804-1.805h-1.173A1.81 1.81 0 0 1 10 20.846h0a1.81 1.81 0 0 1 1.804-1.806h1.082a1.94 1.94 0 0 1 1.804.813");
}

</style>
