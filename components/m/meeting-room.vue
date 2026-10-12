<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="jcp1v29ok"/><rect class="wnyicw7lu"/><path class="w2y6r7bhu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:meeting-room" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jcp1v29ok {
  width: 11.5px;
  height: 6.5px;
  x: 6.25px;
  y: 2.75px;
  rx: 1.5px;
}

.w2y6r7bhu {
  d: path("M8 15.75v5.5m8-5.5v5.5M2.75 11v10.25m0-4h2.5m16-6.25v10.25m0-4h-2.5");
}

.wnyicw7lu {
  width: 13.5px;
  height: 2.5px;
  x: 5.25px;
  y: 13.25px;
  rx: 1.25px;
}

</style>
