<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mk5xfob2d"/><path class="zre4u_y4w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:undo-history" /></template>
<style>
.mk5xfob2d {
  d: path("M5 12a8 8 0 1 1 4 6.928");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zre4u_y4w {
  d: path("m2 9l3 3l3-3m2 0h6m-6 3h6m-6 3h4");
}

</style>
