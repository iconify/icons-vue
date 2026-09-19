<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wfasj_amn"/><circle class="f342dhbpx"/><path class="sigbhsbtj"/><circle class="wmajx68ok"/><path class="nqpttacht"/><circle class="qi-ilao9a"/><circle class="er3stedox"/><circle class="fppr5cbde"/><circle class="g_igvn_mm"/><path class="boe0hsbbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ngpemu" /></template>
<style>
.boe0hsbbz {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  d: path("M31.976 14.44c.754 0 .684.556.684 1.402s.07 13.901.07 14.526s.537 1.187-8.73 1.187s-8.73-.563-8.73-1.187s.07-13.68.07-14.526s-.07-1.402.684-1.402z");
}

.er3stedox {
  cx: 40.565px;
  cy: 19.537px;
  r: 1.183px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.f342dhbpx {
  cx: 8.804px;
  cy: 22.312px;
  r: 3.424px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.fppr5cbde {
  cx: 40.885px;
  cy: 14.468px;
  r: 0.75px;
  fill: currentColor;
}

.g_igvn_mm {
  cx: 10.779px;
  cy: 16.11px;
  r: 0.75px;
  fill: currentColor;
}

.nqpttacht {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-miterlimit: 4.081;
  d: path("M5.645 16.11h1.992");
}

.qi-ilao9a {
  cx: 37.083px;
  cy: 22.312px;
  r: 1.306px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.sigbhsbtj {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  d: path("M17.706 16.979v12.055h12.588V16.979z");
}

.wfasj_amn {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  d: path("M13.422 11.478c-4.618 0-7.613.032-8.768.191C3.5 11.83 3.5 12.688 3.5 13.1v18.047c0 2.222.201 4.004 5.304 4.49s7.161.885 15.196.885s10.093-.398 15.196-.884c5.103-.487 5.304-2.27 5.304-4.491V13.1c0-.412 0-1.27-1.154-1.43s-4.15-.192-8.768-.192z");
}

.wmajx68ok {
  cx: 8.804px;
  cy: 22.312px;
  r: 1.618px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
