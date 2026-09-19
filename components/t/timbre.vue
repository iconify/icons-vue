<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="iegh185eo"/><path class="u9l5uwqvo"/><circle class="aphq8qhld"/><path class="aj6x5xmjf"/><circle class="hcdsm6iiq"/><circle class="jyotg0bpc"/><path class="q7dixmbqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:timbre" /></template>
<style>
.aj6x5xmjf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.033 19.208h3.795m-1.083 11.204h6.396");
}

.aphq8qhld {
  cx: 13.83px;
  cy: 26.127px;
  r: 2.742px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.hcdsm6iiq {
  cx: 32.552px;
  cy: 19.222px;
  r: 1.622px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.iegh185eo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.868 5.113A2.863 2.863 0 0 0 5 7.98v25.89a2.86 2.86 0 0 0 2.868 2.869h23.226l-6.864 6.159h15.902A2.86 2.86 0 0 0 43 40.03l-.07-25.902a2.865 2.865 0 0 0-2.869-2.868H24.83l-1.685-6.159ZM31.095 36.74l-6.266-25.48");
}

.jyotg0bpc {
  cx: 38.03px;
  cy: 30.459px;
  r: 1.622px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.q7dixmbqb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.026 23.201a1.622 1.622 0 1 1 .733 3.154M24.23 42.899l-2.128-5.948m12.397-17.743h4.226m-8.289 5.517h8.289");
}

.u9l5uwqvo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.908 16.824h-3.334v9.395");
}

</style>
