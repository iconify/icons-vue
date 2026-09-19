<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vpj61xb4p"/><path class="oyvdmibnj"/><circle class="dkyrqi1qw"/><circle class="kiyuyzo-l"/><path class="opcxdwbkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tap-wizard-2" /></template>
<style>
.dkyrqi1qw {
  cx: 13.429px;
  cy: 15.411px;
  r: 5.286px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.kiyuyzo-l {
  cx: 5.5px;
  cy: 9.464px;
  r: 0.75px;
  fill: currentColor;
}

.opcxdwbkl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.16 21.357v1.321");
}

.oyvdmibnj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.66 25.321H10.126v-2.643");
}

.vpj61xb4p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m43.16 42.5l-18.5-17.179V5.5H8.805");
}

</style>
