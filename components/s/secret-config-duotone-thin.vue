<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yxow7abeb"/><path class="rlk52sj8y"/><path class="tyien_b-s"/><path class="abnm6smsv"/><path class="dxebngfxk"/><path class="a97qfmbix"/><path class="tb5ui_brh"/><path class="yegul17ht"/><path class="dk412jbfb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:secret-config-duotone-thin" /></template>
<style>
.a97qfmbix {
  d: path("M14 9a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.abnm6smsv {
  d: path("M13 3H6v18h12V8");
}

.dk412jbfb {
  d: path("M8 17h4");
}

.dxebngfxk {
  d: path("M8 9h4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rlk52sj8y {
  fill: currentColor;
  d: path("M14 9a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.tb5ui_brh {
  d: path("M8 13h4");
}

.tyien_b-s {
  fill: currentColor;
  d: path("M14 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.yegul17ht {
  d: path("M14 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.yxow7abeb {
  fill: currentColor;
  d: path("M13 3H6v18h12V8");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
