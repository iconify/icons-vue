<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="hg9uy9dro"/><path class="jrhd20qrl"/><path class="hnpg40b2w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:on-screen-keyboard-sharp" /></template>
<style>
.hg9uy9dro {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 3.75h18.5v16.5H2.75zm0 6.75h18.5");
}

.hnpg40b2w {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 16.75h7");
}

.jrhd20qrl {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.5 13.5h.01m3.49 0h.01m3.99 0h.01m3.49 0h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
