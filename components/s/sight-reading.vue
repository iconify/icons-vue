<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="s8thi1btf"/><path class="a-g282zfq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sight-reading" /></template>
<style>
.a-g282zfq {
  d: path("M14.5 2.5V7H19M8 16a2.5 1.75 0 1 0 5 0a2.5 1.75 0 1 0-5 0Zm5 0V9.75");
}

.s8thi1btf {
  d: path("M5 4.5a2 2 0 0 1 2-2h7.5L19 7v12.5a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
