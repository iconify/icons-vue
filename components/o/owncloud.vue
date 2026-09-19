<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="esnaifb2n"/><path class="r6rpziwsp"/><path class="wt_6tzbys"/><path class="q-quo-llj"/><path class="l7nhfxxim"/><path class="vb4e1s2ud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:owncloud" /></template>
<style>
.esnaifb2n {
  cx: 24px;
  cy: 27.249px;
  r: 7px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.l7nhfxxim {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.611 29.64a5.5 5.5 0 0 1 3.89-9.39m2.095 12.5a3 3 0 1 1-1.822-4.398");
}

.q-quo-llj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.111 23.14a5.5 5.5 0 1 1 9.202-2.467M13.75 33.513A5.5 5.5 0 1 1 11 23.25");
}

.r6rpziwsp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.767 24.3a5.5 5.5 0 1 1-1.217 7.683");
}

.vb4e1s2ud {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.378 21.121a3 3 0 0 1 3.621-4.72M39.5 28.25a3 3 0 1 1-2.121 5.121");
}

.wt_6tzbys {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.5 17.75a5.5 5.5 0 0 1 5.5 5.5");
}

</style>
