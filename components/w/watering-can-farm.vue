<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="co-l-xzbi"/><path class="h5juogyfh"/><path class="yxfbobc_y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:watering-can-farm" /></template>
<style>
.co-l-xzbi {
  width: 11px;
  height: 12.25px;
  x: 3px;
  y: 9px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

.h5juogyfh {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 12.5h11M5.5 9V6.75A1.5 1.5 0 0 1 7 5.25h3a1.5 1.5 0 0 1 1.5 1.5V9m2.5 8l4.5-4.5m-.25-.55l-.75-1.65q-.25-.55.29-.28l2.92 1.46q.54.27-.04.43l-1.59.43q-.58.16-.83-.39");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yxfbobc_y {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M21 14.75h.01m-1.51 3h.01");
}

</style>
