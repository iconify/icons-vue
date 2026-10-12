<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="x209lebeq"/><path class="ibvewsbbq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:two-factor-sharp" /></template>
<style>
.ibvewsbbq {
  d: path("M14.25 16.25h6.5v5h-6.5zm1.5 0v-3h3.5v3");
}

.x209lebeq {
  d: path("M11.75 21.25h-6V2.75h12.5v9m-7.5-6h2.5m-4 4.75h.01m2.74 0h.01m2.74 0h.01");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
