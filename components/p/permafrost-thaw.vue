<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yudiqacsm"/><path class="frkmk1k-t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:permafrost-thaw" /></template>
<style>
.frkmk1k-t {
  d: path("m2.5 7l3.25 3L9 7l3 3l3-3l3.25 3l3.25-3M12 12.75c.75 1 2.25 2.25 2.25 3.25a2.25 2.25 0 0 1-4.5 0c0-1 1.5-2.25 2.25-3.25Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yudiqacsm {
  d: path("M2.5 3h19v18h-19Z");
}

</style>
