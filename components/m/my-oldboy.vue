<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bmlhe7bpz"/><circle class="vh-1ibc9h"/><circle class="tnprv2b-w"/><path class="m5-zwfrve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:my-oldboy" /></template>
<style>
.bmlhe7bpz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.188 40.453A60.9 60.9 0 0 1 18.181 43.5h0a3.284 3.284 0 0 1-3.294-2.736L9.57 9.327a1.02 1.02 0 0 1 .836-1.175l21.5-3.638a1.02 1.02 0 0 1 1.175.836L38.4 36.786a3.284 3.284 0 0 1-2.21 3.667m-16.465-5.878l-.851-5.027m-2.088 2.939l5.027-.851m1.208 7.143l2.03-.343m2.998-.508l2.03-.343");
}

.m5-zwfrve {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m12.247 25.156l1.512-.084A92.2 92.2 0 0 0 34.3 21.58l1.29-.374M13.39 10.83l16.577-2.804l1.879 11.107l-16.577 2.804z");
}

.tnprv2b-w {
  cx: 33.003px;
  cy: 28.974px;
  r: 0.75px;
  fill: currentColor;
}

.vh-1ibc9h {
  cx: 29.751px;
  cy: 31.063px;
  r: 0.75px;
  fill: currentColor;
}

</style>
