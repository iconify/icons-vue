<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="dc8-kybzd"/><rect class="tf7-o_9ab"/><path class="cl5sul6sk"/><rect class="dkstmzb6d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:merger-arrows" /></template>
<style>
.cl5sul6sk {
  d: path("m5.75 10.75l3.5 3.5m0-2.75v2.75H6.5m11.75-3.5l-3.5 3.5m0-2.75v2.75h2.75");
}

.dc8-kybzd {
  width: 6px;
  height: 6px;
  x: 2.75px;
  y: 2.75px;
  rx: 1.5px;
}

.dkstmzb6d {
  width: 7.5px;
  height: 5.5px;
  x: 8.25px;
  y: 15.75px;
  rx: 1.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tf7-o_9ab {
  width: 6px;
  height: 6px;
  x: 15.25px;
  y: 2.75px;
  rx: 1.5px;
}

</style>
