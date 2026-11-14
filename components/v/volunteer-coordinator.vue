<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="iac_bourj"/><path class="h_8vws16r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:volunteer-coordinator" /></template>
<style>
.h_8vws16r {
  d: path("M8.5 2.5h7v4h-7Zm-.5 8h8m-8 4h3.5m4.75 1a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0ZM14.5 22c0-1.75 1.5-2.75 3.5-2.75s3.5 1 3.5 2.75");
}

.iac_bourj {
  d: path("M11.7 21.5H4v-17h16v6.9");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
