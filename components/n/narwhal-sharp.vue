<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="zqfcun6zu"/><path class="sc3k80b1i"/><path class="tqqmtbbbm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:narwhal-sharp" /></template>
<style>
.sc3k80b1i {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.25 12.5h.01");
}

.tqqmtbbbm {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m18.25 10l3-6.75");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.zqfcun6zu {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M19.5 13.5c-.25-3-3-5-7-5S6 11 5 14l-2.25-2.25l1.25 4l-1.25 3.5l3.25-2l1.875 1.25h8.375c2.25 0 3.5-2 3.25-5Z");
}

</style>
