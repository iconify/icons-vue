<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="kqezffzhk"/><path class="qwn4--teq"/><path class="va-cqqbhp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:server-rack-sharp" /></template>
<style>
.kqezffzhk {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 3.25h17.5v7.5H3.25zm0 10h17.5v7.5H3.25z");
}

.qwn4--teq {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.25 7h.01m-.01 10h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.va-cqqbhp {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.25 7h5.5m-5.5 10h5.5");
}

</style>
