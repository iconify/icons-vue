<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mpb62g_8u"/><path class="cskad13og"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pill-crusher" /></template>
<style>
.cskad13og {
  d: path("m9.227 10.048l7.071-7.071l2.475 2.475l-7.071 7.071Z");
}

.mpb62g_8u {
  d: path("M3.5 11H7m9.5 0h4a8.5 8.5 0 0 1-17 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
