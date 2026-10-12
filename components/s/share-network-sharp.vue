<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="v3g6xoxym"/><circle class="a429aqafh"/><circle class="xe53owbmy"/><circle class="qkzqambqp"/><path class="c0_cdihkk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:share-network-sharp" /></template>
<style>
.a429aqafh {
  cx: 4.75px;
  cy: 8.25px;
  r: 2px;
}

.c0_cdihkk {
  d: path("m8.93 12.71l-2.81-3M12 11.5V7m3.07 5.71l2.81-3");
}

.qkzqambqp {
  cx: 19.25px;
  cy: 8.25px;
  r: 2px;
}

.v3g6xoxym {
  cx: 12px;
  cy: 16px;
  r: 3px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xe53owbmy {
  cx: 12px;
  cy: 5px;
  r: 2px;
}

</style>
