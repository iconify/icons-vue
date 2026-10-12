<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="qbn9ahbbt"/><path class="kn-efdc_v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:theater-mode-sharp" /></template>
<style>
.kn-efdc_v {
  d: path("M7.5 12h9m-7-2l-2 2l2 2m5-4l2 2l-2 2");
}

.qbn9ahbbt {
  d: path("M2.75 6.75h18.5v10.5H2.75z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
