<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="zdfkbyzpk"/><path class="f0b3shenl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:vibration-alert" /></template>
<style>
.f0b3shenl {
  d: path("M9 6.25v-3.5h6v3.5m-6 11.5v3.5h6v-3.5M12 9.5V12l1.5 1M4.75 8.5l-2 1.75l2 1.75l-2 1.75l2 1.75m14.5-7l2 1.75l-2 1.75l2 1.75l-2 1.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zdfkbyzpk {
  width: 9.5px;
  height: 11.5px;
  x: 7.25px;
  y: 6.25px;
  rx: 2.5px;
}

</style>
