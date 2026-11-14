<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="eka5_4bzo"/><path class="m866e2bak"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sail-number" /></template>
<style>
.eka5_4bzo {
  d: path("M5.5 2.5C12 6 18 12 19.5 18.5h-14Zm0 16v3");
}

.m866e2bak {
  d: path("m8.5 12.25l2-1.75v5.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
