<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="w-auf2bnw"/><circle class="c12c3kbgx"/><circle class="nopx6ibuz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:moped-sharp" /></template>
<style>
.c12c3kbgx {
  cx: 5.25px;
  cy: 18px;
  r: 2.5px;
}

.nopx6ibuz {
  cx: 18.75px;
  cy: 18px;
  r: 2.5px;
}

.w-auf2bnw {
  d: path("M9.5 8.25H13l-.15.74l-.2 1.02l-.15.74h-3l-.22-.72l-.31-1.06l-.22-.72zM7.75 18H11c2.5 0 3.5-5.5 5.56-7.5m-5.56.25v10m7.05-5.15L14.96 5h-2.21");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
