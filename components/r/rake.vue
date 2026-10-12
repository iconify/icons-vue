<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pjokakbyf"/><rect class="hvc_w_9lp"/><path class="aqzeatbnz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:rake" /></template>
<style>
.aqzeatbnz {
  d: path("M6 15.75v5.5m4-5.5v5.5m4-5.5v5.5m4-5.5v5.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hvc_w_9lp {
  width: 15.5px;
  height: 3px;
  x: 4.25px;
  y: 12.75px;
  rx: 1.5px;
}

.pjokakbyf {
  d: path("M12 2.75v10");
}

</style>
