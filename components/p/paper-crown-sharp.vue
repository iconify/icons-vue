<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="syme0dbcp"/><path class="m78bx_bvn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:paper-crown-sharp" /></template>
<style>
.m78bx_bvn {
  d: path("m4.75 15.14l14.94-1.3l1-.09l.09 1l.21 2.48l.09 1l-1 .09l-14.94 1.3l-1 .09l-.09-1l-.21-2.48l-.09-1zM16.7 14.1l.39 4.48");
}

.syme0dbcp {
  d: path("m3.7 14.33l-.24-4.94l-.05-.9l.59.68l1.05 1.2l.59.68l.25-.87l1.04-3.66l.25-.87l.43.79l1.72 3.21l.43.79l.21-.88l1.12-4.65l.21-.88l.36.82l1.92 4.4l.36.82l.33-.84l1.11-2.74l.33-.84l.44.79l1.51 2.73l.44.79l.5-.75l.77-1.16l.5-.75l.11.89l.6 4.67l.11.89l-.9.08l-15.14 1.32l-.9.08z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
