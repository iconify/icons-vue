<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nzgxhibqs"/><path class="yc_5jnb_s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:monitor-wifi" /></template>
<style>
.nzgxhibqs {
  d: path("M2.5 3.5h19v13h-19Zm9.5 13v4m-4 0h8m-4-8h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yc_5jnb_s {
  d: path("M10.055 10.555a2.75 2.75 0 0 1 3.89 0m-5.32-2.077a5.25 5.25 0 0 1 6.75 0");
}

</style>
