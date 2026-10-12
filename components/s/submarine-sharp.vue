<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="muqfu-a3v"/><path class="lxerl0wdp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:submarine-sharp" /></template>
<style>
.lxerl0wdp {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.5 15.5h.01m3.49 0h.01m3.49 0h.01");
}

.muqfu-a3v {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 11.75h15v7.5h-15zm5 0V8h5.5v3.75ZM11.5 8V4.75H14m4.25 10.75h2.5m0-2.25v4.5");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
