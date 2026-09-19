<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w3mk2cc5i"/><path class="m8jhmbcgm"/><circle class="n3gboibkh"/><circle class="zivyk7p6e"/><path class="pelcswbsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:yahoo-japan-browser" /></template>
<style>
.m8jhmbcgm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.66 33.363c-2.274 2.972-5.324 5.354-8.798 6.748c-3.979-5.07-5.406-12.044-3.738-18.27c1.668-6.224 6.391-11.551 12.372-13.951c3.63 4.626 5.137 10.839 4.105 16.62");
}

.n3gboibkh {
  cx: 32.493px;
  cy: 30.651px;
  r: 6.456px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.pelcswbsb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m37.398 36.944l3.735 3.735l1.368-1.368l-3.735-3.735zm.699-.7l-1.034-1.033");
}

.w3mk2cc5i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.485 37.113a16.68 16.68 0 0 1-10.307 3.566c-9.212 0-16.679-7.467-16.679-16.68h0c0-9.21 7.467-16.678 16.68-16.678v0c9.21 0 16.678 7.467 16.678 16.679h0a16.7 16.7 0 0 1-.48 3.974M26.495 7.89l-8.633 32.22M6.068 19.683l22.36 5.992M10.385 12.206l27.904 7.477M6.068 28.318l20.851 5.587");
}

.zivyk7p6e {
  cx: 32.493px;
  cy: 30.651px;
  r: 4px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
