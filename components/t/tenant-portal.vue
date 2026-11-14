<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ptf-lmb_d"/><path class="j5gh1fblk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tenant-portal" /></template>
<style>
.j5gh1fblk {
  d: path("m8 14l4-3.5l4 3.5v4H8Z");
}

.ptf-lmb_d {
  d: path("M2.5 3.5h19v17h-19Zm0 4h19m-16.25-2h.01m2.49 0h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
