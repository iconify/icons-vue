<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="coy827b5i"/><path class="f97k-1bzn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pen" /></template>
<style>
.coy827b5i {
  d: path("m12 2.5l6.5 7L16 18H8L5.5 9.5Zm0 0v7.25");
}

.f97k-1bzn {
  d: path("M10 11.75a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM8 21h8");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
