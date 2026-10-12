<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="e4n_tbx8j"/><path class="skqqrnkoq"/><circle class="m1-2qib8s"/><circle class="i1s33ac1n"/><circle class="oq_-avw0z"/><circle class="f9bqt7b2a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:virtual-classroom" /></template>
<style>
.e4n_tbx8j {
  width: 16.5px;
  height: 15.5px;
  x: 3.75px;
  y: 2.75px;
  rx: 2px;
}

.f9bqt7b2a {
  cx: 16.13px;
  cy: 14.38px;
  r: 0.75px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i1s33ac1n {
  cx: 16.13px;
  cy: 6.63px;
  r: 0.75px;
}

.m1-2qib8s {
  cx: 7.88px;
  cy: 6.63px;
  r: 0.75px;
}

.oq_-avw0z {
  cx: 7.88px;
  cy: 14.38px;
  r: 0.75px;
}

.skqqrnkoq {
  d: path("M2.75 21.25h18.5M12 2.75v15.5M3.75 10.5h16.5");
}

</style>
