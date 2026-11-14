<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="uv28-57oe"/><path class="xddcc2bdh"/><path class="q7gqw2bbs"/><path class="v6x9tspcc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:rock-cycle" /></template>
<style>
.q7gqw2bbs {
  d: path("M13.75 18.25L12 20l1.75 1.75M8 18.928A8 8 0 0 1 12 4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uv28-57oe {
  d: path("m7.75 14.75l.5-2.75L10 9l4-.25L16.25 12v2.75Zm.5-2.75h8");
}

.v6x9tspcc {
  d: path("M10.25 2.25L12 4l-1.75 1.75");
}

.xddcc2bdh {
  d: path("M16 5.072A8 8 0 0 1 12 20");
}

</style>
