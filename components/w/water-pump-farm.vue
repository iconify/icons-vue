<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="ibg-i2bib"/><rect class="opflazbkq"/><path class="uubfobbon"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:water-pump-farm" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ibg-i2bib {
  width: 4.5px;
  height: 12.5px;
  x: 8.5px;
  y: 5.75px;
  rx: 1.5px;
}

.opflazbkq {
  width: 10px;
  height: 3px;
  x: 5.75px;
  y: 18.25px;
  rx: 1px;
}

.uubfobbon {
  d: path("M8.5 9.75h-4v2m6.25-6v-2.5m2 4l8-3.75M4.5 13c1.1 1.4 1.6 2.3 1.6 3a1.6 1.6 0 0 1-3.2 0c0-.7.5-1.6 1.6-3");
}

</style>
