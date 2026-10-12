<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="zfp8_lbwb"/><path class="s-ur5pfpm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:travel-vlog-sharp" /></template>
<style>
.s-ur5pfpm {
  d: path("M9 15.5c-1.5-1.25-2.25-2.4-2.25-3.75a2.25 2.25 0 0 1 4.5 0c0 1.35-.75 2.5-2.25 3.75Zm6.25-5.25l6-3v9.5l-6-3");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zfp8_lbwb {
  d: path("M2.75 6.25h12.5v11.5H2.75z");
}

</style>
