<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dtrf0abou"/><path class="dz4oksbag"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:voice-control" /></template>
<style>
.dtrf0abou {
  d: path("M9.5 3h5v10h-5Z");
}

.dz4oksbag {
  d: path("M6.5 10.5a5.5 5.5 0 0 0 11 0M12 16v4.5m-9-14v5m18-5v5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
