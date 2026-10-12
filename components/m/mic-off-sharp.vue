<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="f6cxlrkdq"/><path class="hhsw5ygdj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mic-off-sharp" /></template>
<style>
.f6cxlrkdq {
  d: path("M8.25 2.75h7.5v11.5h-7.5z");
}

.hhsw5ygdj {
  d: path("M4.75 10.75a7.25 7.25 0 0 0 14.5 0M12 18v3.25M3.75 3.75l16.5 16.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
