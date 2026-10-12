<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="pu_4pou7s"/><path class="vsw33ccsk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:totem-pole-sharp" /></template>
<style>
.pu_4pou7s {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 2.75h8v18.5H8zm-.74 2.86l-3.77-.72l-.74-.14l.24.71l1.02 3.08l.24.71H8v-3.5zm9.48 0l3.77-.72l.74-.14l-.24.71l-1.02 3.08l-.24.71H16v-3.5zM8.75 9.25h6.5m-6.5 6h6.5m-5-2.25h3.5m-3.5 6h3.5");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.vsw33ccsk {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10.5 6h.01m2.99 0h.01m-3.01 5.25h.01m2.99 0h.01m-3.01 6h.01m2.99 0h.01");
}

</style>
