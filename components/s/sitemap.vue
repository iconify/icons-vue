<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="ht0znacbh"/><path class="wui_a059x"/><rect class="pujcpmbfq"/><rect class="baa1w7byb"/><rect class="rtbsmqt1y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sitemap" /></template>
<style>
.baa1w7byb {
  width: 4px;
  height: 5.5px;
  x: 10px;
  y: 15.75px;
  rx: 1.25px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ht0znacbh {
  width: 6.5px;
  height: 5.25px;
  x: 8.75px;
  y: 2.75px;
  rx: 1.25px;
}

.pujcpmbfq {
  width: 4px;
  height: 5.5px;
  x: 2.75px;
  y: 15.75px;
  rx: 1.25px;
}

.rtbsmqt1y {
  width: 4px;
  height: 5.5px;
  x: 17.25px;
  y: 15.75px;
  rx: 1.25px;
}

.wui_a059x {
  d: path("M12 8v8m-7.25-.25v-2.5a1.5 1.5 0 0 1 1.5-1.5h11.5a1.5 1.5 0 0 1 1.5 1.5v2.5");
}

</style>
