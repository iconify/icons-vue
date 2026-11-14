<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uzs0j-bhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:measurement" /></template>
<style>
.uzs0j-bhd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.017 14.033l9.016-9.016a2.625 2.625 0 0 1 3.712 0l1.238 1.238a2.625 2.625 0 0 1 0 3.712l-9.016 9.016a2.625 2.625 0 0 1-3.712 0l-1.238-1.238a2.625 2.625 0 0 1 0-3.712m1.326-1.326l2.475 2.475m-.354-4.596L9.879 12m.707-3.536l2.475 2.475m-.354-4.596l1.414 1.414");
}

</style>
