<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="rh2140hgr"/><path class="mqbcq6bbi"/><circle class="n-dokxb-c"/><path class="opr54_b6k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:resume-sharp" /></template>
<style>
.mqbcq6bbi {
  d: path("M13.75 2.75v5.5h5.5");
}

.n-dokxb-c {
  cx: 9.25px;
  cy: 10.5px;
  r: 1.75px;
}

.opr54_b6k {
  d: path("M13 11.75h2.25m-7 3.5h7.5M8.25 18h7.5");
}

.rh2140hgr {
  d: path("M13.75 2.75h-9v18.5h14.5v-13Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
