<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="dpb-50sbl"/><rect class="iey2l0bmq"/><rect class="xafv9k1ml"/><path class="arhqmbc4o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sleep-tracker" /></template>
<style>
.arhqmbc4o {
  d: path("M11.61 8.5a3.5 3.5 0 1 0 3.57 4.17a2.75 2.75 0 0 1-3.57-4.17");
}

.dpb-50sbl {
  width: 7.5px;
  height: 3.5px;
  x: 8.25px;
  y: 2.75px;
  rx: 1px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iey2l0bmq {
  width: 7.5px;
  height: 3.5px;
  x: 8.25px;
  y: 17.75px;
  rx: 1px;
}

.xafv9k1ml {
  width: 12.5px;
  height: 11.5px;
  x: 5.75px;
  y: 6.25px;
  rx: 3px;
}

</style>
