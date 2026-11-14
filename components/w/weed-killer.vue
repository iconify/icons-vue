<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cjy1i_bre"/><path class="cuibgebzi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:weed-killer" /></template>
<style>
.cjy1i_bre {
  d: path("M5 10h9v11.5H5Zm1.5 0V4.5h9V7H12v3");
}

.cuibgebzi {
  d: path("M8 18.5c0-3 1.25-5 3.25-5c0 3-1.25 5-3.25 5ZM18.75 4h.01m-.01 3.5h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
