<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wvxot9bme"/><path class="zjl_1_bbc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:prescription-pad" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wvxot9bme {
  d: path("M4 4.5h16v17H4Zm4-2v4m4-4v4m4-4v4");
}

.zjl_1_bbc {
  d: path("M8.5 19.5V11h2.75c1.25 0 2.25 1 2.25 2.25c0 1-1 2-2.25 2H8.5m2.75 0l4.25 4.5m0-4l-3.25 4");
}

</style>
