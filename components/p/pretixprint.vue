<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v-i5w1bcc"/><path class="k02gnk0ay"/><path class="mlkclge_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pretixprint" /></template>
<style>
.k02gnk0ay {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.86 21.24v18h20.28v-18Z");
}

.mlkclge_k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.8 34.74v-8h2.6a2.7 2.7 0 0 1 0 5.4h-2.6");
}

.v-i5w1bcc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 13.44h39a4.66 4.66 0 0 0-4.64-4.68H9.18a4.69 4.69 0 0 0-4.68 4.68m0 0v12.48a4.65 4.65 0 0 0 4.62 4.68h4.74v-9.36h20.28v9.36h4.68a4.65 4.65 0 0 0 4.68-4.62V13.44Z");
}

</style>
