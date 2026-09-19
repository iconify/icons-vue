<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="men496w1a"/><path class="div3ai0_u"/><path class="pywj9nd4v"/><path class="wvmscsb0u"/><path class="m94wnybpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mts-pay" /></template>
<style>
.div3ai0_u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.452 21.821v12.504a3.28 3.28 0 0 1-3.288 3.289H11.678a3.28 3.28 0 0 1-3.289-3.289v-2.399");
}

.m94wnybpl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m12.254 13.351l1.222-4.561l1.06 5.178l3.505-3.948l-1.222 4.56m18.316.014l2.958.792m-2.702 4.17l1.223-4.566m-2.153 13.953l-.005.019c-.224.835-1.067 1.335-1.884 1.116s-1.298-1.073-1.074-1.909l.413-1.54c.224-.836 1.067-1.336 1.884-1.117s1.298 1.073 1.074 1.909l-.005.018");
}

.men496w1a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m40.454 25.016l1.374 10.44a3.28 3.28 0 0 1-2.83 3.689l-25.27 3.325a3.28 3.28 0 0 1-3.69-2.83l-.355-2.701");
}

.pywj9nd4v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.034 17.134q.004.241-.028.488l-2.04 15.487a3.28 3.28 0 0 1-3.689 2.831L10.01 32.615a3.28 3.28 0 0 1-2.83-3.69l.314-2.392");
}

.wvmscsb0u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m14.327 5.614l24.618 6.596a3.28 3.28 0 0 1 2.325 4.028l-4.043 15.088A3.28 3.28 0 0 1 33.2 33.65L8.582 27.055a3.28 3.28 0 0 1-2.325-4.028L10.299 7.94a3.28 3.28 0 0 1 4.028-2.325");
}

</style>
