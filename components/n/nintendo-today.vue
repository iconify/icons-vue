<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qvo1bobsl"/><circle class="c66au--wp"/><circle class="ym4dxjkdd"/><circle class="ak0qpxbua"/><circle class="pspmopb5i"/><path class="mywl7acvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nintendo-today" /></template>
<style>
.ak0qpxbua {
  cx: 9.94px;
  cy: 38.09px;
  r: 1.35px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.c66au--wp {
  cx: 37.99px;
  cy: 9.91px;
  r: 1.35px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.mywl7acvp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.5 42.5h-33l-2-2v-33l2-2h33l2 2v33z");
}

.pspmopb5i {
  cx: 9.91px;
  cy: 9.94px;
  r: 1.35px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.qvo1bobsl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.412 36.945v-4.07h-6.64v4.07zm0-10.5l.763-.763h4.31l3.12-3.12v-8.54l-3.01-3.01h-17.2l-3.01 3.01v6.56h6.64v-4.07l.94-.94h8.06l.94.94v4.07l-.73.73h-4.49l-2.98 2.98v6.23h6.64v-4.07");
}

.ym4dxjkdd {
  cx: 38.09px;
  cy: 37.99px;
  r: 1.35px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
