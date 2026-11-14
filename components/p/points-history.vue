<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zg_875wcp"/><path class="l18l-ccti"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:points-history" /></template>
<style>
.l18l-ccti {
  d: path("M4.5 4v4h4m3.5.5v4l3 2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zg_875wcp {
  d: path("M4.5 12A7.5 7.5 0 1 0 7 6.5");
}

</style>
