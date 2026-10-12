<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dlx1kfxsa"/><circle class="upu83lbfh"/><path class="lj9r6l14u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:timesheet" /></template>
<style>
.dlx1kfxsa {
  d: path("M10.75 20.25h-4.5a2.5 2.5 0 0 1-2.5-2.5v-12a2.5 2.5 0 0 1 2.5-2.5h11.5a2.5 2.5 0 0 1 2.5 2.5v5m-13-3h9.5m-9.5 3.5h5.25m-5.25 3.5h3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lj9r6l14u {
  d: path("M17 15v2l1.25.75");
}

.upu83lbfh {
  cx: 17px;
  cy: 17px;
  r: 4.25px;
}

</style>
