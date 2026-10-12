<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="zhj4drbyr"/><circle class="t14991bsq"/><path class="gyn74xtus"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:wedding-rings" /></template>
<style>
.gyn74xtus {
  d: path("M13.65 4h3.2q.4 0 .66.31l.73.88q.26.31-.03.58l-2.67 2.46q-.29.27-.58 0l-2.67-2.46q-.29-.27-.03-.58l.73-.88q.26-.31.66-.31");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.t14991bsq {
  cx: 15.25px;
  cy: 14.75px;
  r: 5.5px;
}

.zhj4drbyr {
  cx: 8.75px;
  cy: 14.75px;
  r: 5.5px;
}

</style>
