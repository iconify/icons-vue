<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="m10ymsugb"/><path class="s_yqvibim"/><circle class="mc92kqbrb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:orbit-sharp" /></template>
<style>
.m10ymsugb {
  cx: 12px;
  cy: 12px;
  r: 3.5px;
}

.mc92kqbrb {
  cx: 17.83px;
  cy: 6.17px;
  r: 2px;
}

.s_yqvibim {
  d: path("M19.07 7.74a8.25 8.25 0 1 1-2.81-2.81");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
