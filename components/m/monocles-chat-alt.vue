<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nnzs-xbql"/><circle class="bp0kskbyq"/><circle class="b-op2ezlh"/><path class="t2uo43fek"/><circle class="eoepqvbrm"/><circle class="gy6tecbzf"/><path class="ezec3nb3g"/><circle class="maclm5blr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:monocles-chat-alt" /></template>
<style>
.b-op2ezlh {
  cx: 36.67px;
  cy: 19.683px;
  r: 0.75px;
  fill: currentColor;
}

.bp0kskbyq {
  cx: 30.443px;
  cy: 19.683px;
  r: 3.532px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.eoepqvbrm {
  cx: 17.557px;
  cy: 19.683px;
  r: 3.532px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ezec3nb3g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M2.5 24C2.5 12.126 12.126 2.5 24 2.5S45.5 12.126 45.5 24h0c0 11.874-9.626 21.5-21.5 21.5a21.6 21.6 0 0 1-10.327-2.637l-9.638 1.102l1.102-9.638A21.6 21.6 0 0 1 2.5 24");
}

.gy6tecbzf {
  cx: 11.331px;
  cy: 19.683px;
  r: 0.75px;
  fill: currentColor;
}

.maclm5blr {
  cx: 24px;
  cy: 24px;
  r: 18.12px;
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
}

.nnzs-xbql {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.003 27.645s1.267-.993 2.043-.614c2.601 1.272 3.739 5.11 9.165 2.173c-3.703 6.739-9.6 3.867-11.207 1.509c-1.606 2.358-7.503 5.23-11.207-1.509c5.426 2.937 6.564-.902 9.165-2.173c.775-.38 2.041.614 2.041.614m12.667-.446v-4.664");
}

.t2uo43fek {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.331 27.199v-4.664");
}

</style>
