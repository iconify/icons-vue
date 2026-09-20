<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="hzwd9ccnz"/><circle class="ewwkavb8u"/><circle class="iuf-g2bzj"/><circle class="bx8tmhbti"/><circle class="rkpi26b-t"/><circle class="d2ic5ybid"/><circle class="fb6wc-bcd"/><path class="s-4qombze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:studentsorost" /></template>
<style>
.bx8tmhbti {
  cx: 10.285px;
  cy: 19.493px;
  r: 6.203px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.d2ic5ybid {
  cx: 26.762px;
  cy: 38.297px;
  r: 6.203px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ewwkavb8u {
  cx: 35.098px;
  cy: 14.55px;
  r: 6.203px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.fb6wc-bcd {
  cx: 13.193px;
  cy: 33.644px;
  r: 6.203px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.hzwd9ccnz {
  cx: 23.951px;
  cy: 23.951px;
  r: 6.203px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.iuf-g2bzj {
  cx: 21.141px;
  cy: 9.703px;
  r: 6.203px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.rkpi26b-t {
  cx: 37.715px;
  cy: 28.895px;
  r: 6.203px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.s-4qombze {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.916 26.86c.582.484.97.58 2.133.58h.581c.872 0 1.648-.774 1.648-1.647c0-.872-.775-1.648-1.648-1.648h-1.26c-.872 0-1.648-.775-1.648-1.647c0-.873.776-1.648 1.648-1.648h.582c1.26 0 1.648.097 2.132.581");
}

</style>
