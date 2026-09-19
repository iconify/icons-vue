<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r1m6yabyb"/><path class="bbga-_bkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:vesselfinder" /></template>
<style>
.bbga-_bkg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.404 33.014L3.325 15.071l10.416 18.017m5.128-9.045l5.271-9.13l5.272 9.13m-5.273-9.131v12.173M3.327 15.071l17.45 5.66m6.749.048l17.149-5.549");
}

.r1m6yabyb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m13.743 33.088l30.93-17.858l-10.268 17.784z");
}

</style>
