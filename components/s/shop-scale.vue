<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="jolwk_1dx"/><path class="ip2emh-hq"/><rect class="jh2trtb0z"/><path class="qj-xzs08j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:shop-scale" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ip2emh-hq {
  d: path("M16 5.75h3m-1.5 3v5.5m-14.75-3h10.5m-5.25 0v3");
}

.jh2trtb0z {
  width: 18.5px;
  height: 7px;
  x: 2.75px;
  y: 14.25px;
  rx: 2px;
}

.jolwk_1dx {
  width: 7.5px;
  height: 6px;
  x: 13.75px;
  y: 2.75px;
  rx: 1.5px;
}

.qj-xzs08j {
  d: path("M6 17.75h3");
}

</style>
