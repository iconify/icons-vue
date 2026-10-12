<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="f-qbcacln"/><path class="pb0oqlbgj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:overpass" /></template>
<style>
.f-qbcacln {
  width: 7.5px;
  height: 18.5px;
  x: 8.25px;
  y: 2.75px;
  rx: 1.25px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pb0oqlbgj {
  d: path("M12 5.25v2.5m0 3v2.5m0 3v2.5m-9.25-10H6.5m11 0h3.75m-18.5 6.5H6.5m11 0h3.75");
}

</style>
