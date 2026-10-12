<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="a_xhlzb6p"/><circle class="tohuynb8p"/><circle class="ep-20ju6p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:paint-splatter-sharp" /></template>
<style>
.a_xhlzb6p {
  d: path("m12.22 7.07l.27.65l.6 1.48l1.6.02l.71.01l1.6.02l-.79 1.4l-.34.61l-.78 1.4l.98 1.26l.43.56l.98 1.26l-1.58.26l-.69.11l-1.58.26l-.38 1.56l-.17.68l-.37 1.56l-1.19-1.08l-.52-.47l-1.19-1.07l-1.45.67l-.64.3l-1.45.68l.1-1.6l.05-.7l.1-1.6l-1.44-.72l-.63-.31l-1.43-.71l1.31-.92l.58-.4l1.31-.92l-.34-1.57l-.14-.69L5.4 7.5l1.54.45l.67.2l1.54.45l1.01-1.23l.45-.55l1.01-1.24z");
}

.ep-20ju6p {
  cx: 19.75px;
  cy: 18.25px;
  r: 1.25px;
}

.tohuynb8p {
  cx: 19.25px;
  cy: 4.75px;
  r: 1.5px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
