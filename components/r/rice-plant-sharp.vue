<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="lvaltwbsz"/><path class="xka--yjda"/><path class="oij1--bku"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:rice-plant-sharp" /></template>
<style>
.lvaltwbsz {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 21.25V12c0-3.5 1.5-6.5 4.25-8.5C17 3.75 19 6.25 19.5 10.25");
}

.oij1--bku {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15.5 7h.01m1.99 3.25h.01m2.24 3.25h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.xka--yjda {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 18.5c-.75-2.25-2.75-4-6.25-5m6.25 2l.776-1.94l2.474-1.06");
}

</style>
