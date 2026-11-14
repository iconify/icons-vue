<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e_19yjbwc"/><path class="nka5uubfm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:traffic-light-arrow-right" /></template>
<style>
.e_19yjbwc {
  d: path("M7 2h10v20H7Z");
}

.nka5uubfm {
  d: path("M10.5 6.25a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm0 5.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm-.5 5.75h4m-1.5-1.5l1.5 1.5l-1.5 1.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
