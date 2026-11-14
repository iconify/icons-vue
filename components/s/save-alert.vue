<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="uuozo9bxc"/><path class="pm9-gsv4x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:save-alert" /></template>
<style>
.pm9-gsv4x {
  d: path("M8 4v3a1 1 0 0 0 1 1h5a1 1 0 0 0 1-1V4m3 10.5v3.25m0 3h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uuozo9bxc {
  d: path("M4 4h12.5L20 7.5v4.75h-7.75V20H4Z");
}

</style>
