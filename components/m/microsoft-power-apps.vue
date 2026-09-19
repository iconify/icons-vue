<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c1nd_5b8g"/><path class="gejadvbjo"/><path class="u61-9bejp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:microsoft-power-apps" /></template>
<style>
.c1nd_5b8g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.92 8.059L22.433 6.57a2 2 0 0 0-2.93.11L4.852 23.704a2 2 0 0 0 .103 2.719l14.942 14.941a2 2 0 0 0 2.93-.11l1.186-1.379");
}

.gejadvbjo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m20.165 15.403l6.175 6.174a2 2 0 0 1 .102 2.72l-7.118 8.272a2 2 0 0 0 .102 2.718l6.142 6.143a2 2 0 0 0 2.93-.11l14.65-17.024a2 2 0 0 0-.103-2.718L28.103 6.636a2 2 0 0 0-2.93.11l-5.11 5.938a2 2 0 0 0 .102 2.718");
}

.u61-9bejp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m39.24 28.836l-1.206 1.399a2 2 0 0 1-2.928.108l-6.141-6.141a2 2 0 0 1-.102-2.719l5.11-5.938a2 2 0 0 1 2.93-.11l1.35 1.351");
}

</style>
