<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="neldvtb9y"/><rect class="l29yxlbke"/><rect class="ojig9-but"/><path class="d5nbovbqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pc-simulator" /></template>
<style>
.d5nbovbqg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.75 24.5h9.5a2.25 2.25 0 0 1 2.25 2.25h0A2.25 2.25 0 0 1 40.25 29h-9.5a2.25 2.25 0 0 1-2.25-2.25h0a2.25 2.25 0 0 1 2.25-2.25m0 4.5h9.5a2.25 2.25 0 0 1 2.25 2.25h0a2.25 2.25 0 0 1-2.25 2.25h-9.5a2.25 2.25 0 0 1-2.25-2.25h0A2.25 2.25 0 0 1 30.75 29m0 4.5h9.5a2.25 2.25 0 0 1 2.25 2.25h0A2.25 2.25 0 0 1 40.25 38h-9.5a2.25 2.25 0 0 1-2.25-2.25h0a2.25 2.25 0 0 1 2.25-2.25m0 4.5h9.5a2.25 2.25 0 0 1 2.25 2.25h0a2.25 2.25 0 0 1-2.25 2.25h-9.5a2.25 2.25 0 0 1-2.25-2.25h0A2.25 2.25 0 0 1 30.75 38M9.472 21.95v-8h2.619c1.48 0 2.68 1.203 2.68 2.687s-1.2 2.686-2.68 2.686H9.47m12.201-.056v.033a2.65 2.65 0 1 1-5.3 0v-2.7a2.65 2.65 0 1 1 5.3 0v.033");
}

.l29yxlbke {
  width: 14.857px;
  height: 11.1px;
  x: 27.643px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
  ry: 2px;
}

.neldvtb9y {
  width: 20.143px;
  height: 24.9px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
  ry: 2px;
}

.ojig9-but {
  width: 15.857px;
  height: 10.1px;
  x: 5.5px;
  y: 32.3px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
  ry: 2px;
}

</style>
