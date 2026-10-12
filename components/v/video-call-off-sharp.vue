<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="zfp8_lbwb"/><path class="xvr4rhy1x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:video-call-off-sharp" /></template>
<style>
.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xvr4rhy1x {
  d: path("m15.25 10.25l4.4-2.45l1.6-1.2v10.8l-1.6-1.2l-4.4-2.45Zm-12.5-5.5l16.5 16.5");
}

.zfp8_lbwb {
  d: path("M2.75 6.25h12.5v11.5H2.75z");
}

</style>
