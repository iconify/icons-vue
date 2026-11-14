<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="m0gxfb3hd"/><path class="cpscrt0jg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:medical-coding" /></template>
<style>
.cpscrt0jg {
  d: path("M6 7.25a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0ZM12.25 11l-1 5.5m4-6l-1 5.5M10 12.75h6.25M9.5 15h6.25");
}

.m0gxfb3hd {
  d: path("M3 3h8l10 10l-8 8L3 11Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
