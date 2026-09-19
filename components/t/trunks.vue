<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qm96ehbwj"/><circle class="b3j0jtb7q"/><circle class="sqnkh4bjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:trunks" /></template>
<style>
.b3j0jtb7q {
  cx: 19.997px;
  cy: 14.573px;
  r: 0.75px;
  fill: currentColor;
}

.qm96ehbwj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 9.2h-3.837L8.619 4.5l-2.457 9.075l1.13 10.882l11.226-3.707l3.318 22.75H24m0-34.3h3.837l11.544-4.7l2.457 9.075l-1.13 10.882l-11.226-3.707l-3.318 22.75H24");
}

.sqnkh4bjq {
  cx: 28.003px;
  cy: 14.573px;
  r: 0.75px;
  fill: currentColor;
}

</style>
