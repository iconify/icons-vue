<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="rsea1pbos"/><path class="ph8xawbhr"/><path class="pjk26tbre"/><path class="v632f1b0b"/><path class="jrnrnf6mq"/><path class="jpgroib-x"/><path class="zuquf0b8s"/><path class="fcstqn4mf"/><path class="sjot3p-qh"/><path class="aoxrbobxu"/><path class="qrln8gb_a"/><path class="ktpncgb0v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:websocket-close-duotone-bold" /></template>
<style>
.aoxrbobxu {
  d: path("M14 8h4");
}

.fcstqn4mf {
  d: path("M18 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.jpgroib-x {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M10 16H6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jrnrnf6mq {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M18 16h-4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ktpncgb0v {
  d: path("M10 16H6");
}

.ph8xawbhr {
  fill: currentColor;
  d: path("M18 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.pjk26tbre {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 8h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qrln8gb_a {
  d: path("M18 16h-4");
}

.rsea1pbos {
  fill: currentColor;
  d: path("M2 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.sjot3p-qh {
  d: path("M6 8h4");
}

.v632f1b0b {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M14 8h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zuquf0b8s {
  d: path("M2 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
