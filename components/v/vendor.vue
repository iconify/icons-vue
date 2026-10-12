<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="im8lz_bbl"/><circle class="ytopibb5c"/><path class="jk8xifbqq"/><rect class="ukiulz-bh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:vendor" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.im8lz_bbl {
  d: path("M6.5 2.75h11l2.25 2.5H4.25ZM5 5.25V17M19 5.25V17");
}

.jk8xifbqq {
  d: path("M8 17c0-1.6 1.8-2.5 4-2.5s4 .9 4 2.5Z");
}

.ukiulz-bh {
  width: 18.5px;
  height: 4.25px;
  x: 2.75px;
  y: 17px;
  rx: 1.5px;
}

.ytopibb5c {
  cx: 12px;
  cy: 10px;
  r: 2px;
}

</style>
