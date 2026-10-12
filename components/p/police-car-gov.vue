<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dhenzzulg"/><circle class="gsab0-usu"/><circle class="v8hd6uj2s"/><rect class="hwdm4objn"/><path class="hqf3g7b9x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:police-car-gov" /></template>
<style>
.dhenzzulg {
  d: path("M2.75 16.5v-2.75a1.5 1.5 0 0 1 1.15-1.46l2.6-.64L9 8.45a2 2 0 0 1 1.6-.75h4.15a2 2 0 0 1 1.5.68L19 11.65l1.1.25a1.5 1.5 0 0 1 1.15 1.46v3.14a1 1 0 0 1-1 1h-.75a2.25 2.25 0 0 0-4.5 0H9a2.25 2.25 0 0 0-4.5 0h-.75a1 1 0 0 1-1-1");
}

.gsab0-usu {
  cx: 6.75px;
  cy: 17.5px;
  r: 2.25px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hqf3g7b9x {
  d: path("M6.75 11.75h12M12.5 8v3.75");
}

.hwdm4objn {
  width: 4px;
  height: 2.5px;
  x: 10.5px;
  y: 5.25px;
  rx: 1px;
}

.v8hd6uj2s {
  cx: 17.25px;
  cy: 17.5px;
  r: 2.25px;
}

</style>
