<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wawub773b"/><circle class="t85fvx20g"/><circle class="e7x-5jlpy"/><circle class="hysscebvf"/><circle class="djv6_q4jg"/><circle class="e40d5qsap"/><circle class="ffx19dbjx"/><circle class="orqtzvbgq"/><circle class="hx2q6bc5e"/><path class="u3vcj5xhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sente-online-go" /></template>
<style>
.djv6_q4jg {
  cx: 29px;
  cy: 29px;
  r: 3.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.e40d5qsap {
  cx: 39px;
  cy: 29px;
  r: 3.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.e7x-5jlpy {
  cx: 19px;
  cy: 9px;
  r: 3.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ffx19dbjx {
  cx: 19px;
  cy: 29px;
  r: 3.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.hx2q6bc5e {
  cx: 29px;
  cy: 39px;
  r: 3.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.hysscebvf {
  cx: 29px;
  cy: 19px;
  r: 3.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.orqtzvbgq {
  cx: 9px;
  cy: 29px;
  r: 3.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.t85fvx20g {
  cx: 19px;
  cy: 19px;
  r: 3.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.u3vcj5xhm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.5 29h3m7 0h3m-3-10h3m7 10h3M19 12.5v3m0 7v3m10 7v3m0-13v3m-10 7V39m10-23.5V9m3.5 10H39m-23.5 0H9");
}

.wawub773b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9 25.5V11a2 2 0 0 1 2-2h4.5m10 30H11a2 2 0 0 1-2-2v-4.5m30 0V37a2 2 0 0 1-2 2h-4.5m-10-30H37a2 2 0 0 1 2 2v14.5");
}

</style>
