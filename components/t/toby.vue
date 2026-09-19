<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="naf11hb6l"/><circle class="qph1m4ics"/><path class="agnn386zg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:toby" /></template>
<style>
.agnn386zg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.11 17.5c9.783 0 5.623-12.297 15.577-11.994");
}

.naf11hb6l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.5 17.5a6 6 0 0 1 0-12h25a6 6 0 0 1 0 12zm18.5 19a6 6 0 0 1-12 0v-15h12z");
}

.qph1m4ics {
  cx: 36.5px;
  cy: 11.5px;
  r: 2.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
