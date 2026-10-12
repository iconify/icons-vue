<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="wybe_-bli"/><circle class="m1-2qib8s"/><circle class="i1s33ac1n"/><circle class="oq_-avw0z"/><circle class="f9bqt7b2a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:virtual-classroom-sharp" /></template>
<style>
.f9bqt7b2a {
  cx: 16.13px;
  cy: 14.38px;
  r: 0.75px;
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

.wybe_-bli {
  d: path("M3.75 2.75h16.5v15.5H3.75zm-1 18.5h18.5M12 2.75v15.5M3.75 10.5h16.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
