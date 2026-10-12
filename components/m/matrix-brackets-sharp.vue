<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="kaawtd2jl"/><circle class="u1a9bn6oe"/><circle class="zczcnxb6y"/><circle class="frskmbb5i"/><circle class="ilmmol0fy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:matrix-brackets-sharp" /></template>
<style>
.frskmbb5i {
  cx: 9.5px;
  cy: 15px;
  r: 1.25px;
}

.ilmmol0fy {
  cx: 14.5px;
  cy: 15px;
  r: 1.25px;
}

.kaawtd2jl {
  d: path("M7.25 3.75H4.5v16.5h2.75m9.5-16.5h2.75v16.5h-2.75");
}

.u1a9bn6oe {
  cx: 9.5px;
  cy: 9px;
  r: 1.25px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zczcnxb6y {
  cx: 14.5px;
  cy: 9px;
  r: 1.25px;
}

</style>
