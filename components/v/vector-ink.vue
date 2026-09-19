<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ud6ow8byy"/><circle class="ff21hpbgc"/><circle class="agt5ddbya"/><circle class="xljmdcbza"/><circle class="g29fsqb5k"/><circle class="l7umoikdj"/><circle class="tlo37tbdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:vector-ink" /></template>
<style>
.agt5ddbya {
  cx: 39.954px;
  cy: 15.196px;
  r: 2.404px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ff21hpbgc {
  cx: 39.954px;
  cy: 23.596px;
  r: 2.404px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.g29fsqb5k {
  cx: 39.954px;
  cy: 38.081px;
  r: 2.404px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.l7umoikdj {
  cx: 28.862px;
  cy: 36.343px;
  r: 2.404px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.tlo37tbdo {
  cx: 11.166px;
  cy: 26.803px;
  r: 2.404px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ud6ow8byy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m5.641 26.6l27.29 14.508m-27.29-20.1l27.29 14.835M26.458 5.5v37m4.808-37v37M37.55 20v21.618M42.359 20v21.618");
}

.xljmdcbza {
  cx: 28.862px;
  cy: 12.792px;
  r: 2.404px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
