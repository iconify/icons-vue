<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qcbwp5emp"/><path class="dri233bjf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:nunchaku-training" /></template>
<style>
.dri233bjf {
  d: path("M5.5 7.5c0-4.5 6-5.5 6.75-1.75");
}

.qcbwp5emp {
  d: path("M3.5 7.5h4v13h-4Zm7.018-.629l3.464-2l6.5 11.258l-3.464 2Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
