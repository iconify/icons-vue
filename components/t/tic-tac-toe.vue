<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tty1brbkd"/><circle class="ep3ufxb5g"/><circle class="u8ih3acmi"/><circle class="rmcxtcyms"/><circle class="kwkouxb0h"/><circle class="e8lr1by8q"/><path class="qpln7slcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tic-tac-toe" /></template>
<style>
.e8lr1by8q {
  cx: 10.883px;
  cy: 10.937px;
  r: 3.57px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ep3ufxb5g {
  cx: 24px;
  cy: 24px;
  r: 3.57px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.kwkouxb0h {
  cx: 10.883px;
  cy: 37.007px;
  r: 3.57px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.qpln7slcj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m20.917 14.019l6.166-6.165m-6.166 0l6.166 6.165m-6.166 26.07l6.166-6.165m-6.166 0l6.166 6.165M7.801 26.973l6.165-6.166m-6.165 0l6.165 6.166");
}

.rmcxtcyms {
  cx: 36.396px;
  cy: 37.007px;
  r: 3.57px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.tty1brbkd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.833 5.5v37m12.334-37v37M42.5 17.833h-37m37 12.334h-37");
}

.u8ih3acmi {
  cx: 36.396px;
  cy: 24px;
  r: 3.57px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
