<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="i18uhxbuh"/><circle class="o_d4tnb4s"/><path class="c6d4l54yc"/><circle class="ssv5_6pyh"/><circle class="i3mci3hka"/><path class="fatvfzbrk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:notistar" /></template>
<style>
.c6d4l54yc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.01 26.267h29.98a2.5 2.5 0 0 1 2.498 2.499v11.237A2.5 2.5 0 0 1 38.99 42.5H9.01a2.5 2.5 0 0 1-2.499-2.498V28.765a2.5 2.5 0 0 1 2.497-2.498M9.01 5.5h29.98a2.5 2.5 0 0 1 2.498 2.498v11.237a2.5 2.5 0 0 1-2.497 2.498H9.01a2.5 2.5 0 0 1-2.499-2.499V7.997A2.5 2.5 0 0 1 9.01 5.5");
}

.fatvfzbrk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.447 9.41h10.45m5.809 0h6.784m-6.784 21.088h6.784m-23.16 0h10.626M9.673 37.602H20.3M9.673 16.378H20.3");
}

.i18uhxbuh {
  cx: 35.679px;
  cy: 37.443px;
  r: 2.811px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.i3mci3hka {
  cx: 35.679px;
  cy: 16.378px;
  r: 2.811px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.o_d4tnb4s {
  cx: 10.884px;
  cy: 9.411px;
  r: 1.249px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ssv5_6pyh {
  cx: 10.922px;
  cy: 30.498px;
  r: 1.249px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
