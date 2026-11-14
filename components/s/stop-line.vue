<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="liukvs2qv"/><path class="evelys07t"/><path class="i2-ny_bzf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:stop-line" /></template>
<style>
.evelys07t {
  fill: currentColor;
  d: path("M5.75 11.5h12.5v3H5.75Z");
}

.i2-ny_bzf {
  d: path("M12 3v4");
}

.liukvs2qv {
  d: path("M3 2.5v19m18-19v19");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
