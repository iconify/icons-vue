<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="dnp2npbye"/><circle class="c3rr-6blb"/><path class="xpbb2cdtq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:passport-photo" /></template>
<style>
.c3rr-6blb {
  cx: 12px;
  cy: 10.25px;
  r: 3.75px;
}

.dnp2npbye {
  width: 14.5px;
  height: 18.5px;
  x: 4.75px;
  y: 2.75px;
  rx: 2.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xpbb2cdtq {
  d: path("M8.25 10.25h7.5M12 6.5a7.5 7.5 0 0 0 0 7.5m-3 3.5h6");
}

</style>
