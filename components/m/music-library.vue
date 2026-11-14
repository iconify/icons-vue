<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qd4vd5b4k"/><path class="zv8qcxb7y"/><path class="ias00wbuv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:music-library" /></template>
<style>
.ias00wbuv {
  d: path("M14.25 13V7l3.25 1");
}

.qd4vd5b4k {
  d: path("M6.5 3.5h15v14h-15Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zv8qcxb7y {
  d: path("M3 8v10a2.5 2.5 0 0 0 2.5 2.5h11M10.75 13a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Z");
}

</style>
