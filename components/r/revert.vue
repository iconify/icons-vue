<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xj7nnm-0n"/><path class="hs4ne2wsc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:revert" /></template>
<style>
.hs4ne2wsc {
  d: path("M11 6L8 9l3 3M4 5v8");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xj7nnm-0n {
  d: path("M20 19v-5a5 5 0 0 0-5-5H8");
}

</style>
