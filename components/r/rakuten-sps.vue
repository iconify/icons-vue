<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="e-1q5_dez"/><path class="fmqppmdec"/></g><path class="fcnl5gb0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:rakuten-sps" /></template>
<style>
.e-1q5_dez {
  d: path("M20.843 11.802a14.6 14.6 0 0 1 8.048-2.418C36.959 9.384 43.5 15.928 43.5 24c0 8.073-6.54 14.617-14.609 14.617a14.6 14.6 0 0 1-9.05-3.143");
}

.fcnl5gb0u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.223 18.504H11m4.698 11.736H4.5m13.46-5.868H7.813");
}

.fmqppmdec {
  d: path("M25.234 30.99V17.01h4.634c2.673 0 4.811 2.097 4.811 4.718s-2.138 4.718-4.812 4.718h-4.633");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
