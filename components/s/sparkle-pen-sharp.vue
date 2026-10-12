<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ixiwpjb5l"/><path class="a1ocfmb_d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sparkle-pen-sharp" /></template>
<style>
.a1ocfmb_d {
  d: path("M10 10.25a1.25 1.25 0 1 1 0 2.5a1.25 1.25 0 1 1 0-2.5m8.25-7.5l.36 2.64l2.64.36l-2.64.36l-.36 2.64l-.36-2.64l-2.64-.36l2.64-.36z");
}

.ixiwpjb5l {
  d: path("M7.75 3h5.5v4.5l.48.88l1.79 3.24l.48.88l-.57.82l-4.86 7.11l-.57.82l-.57-.82l-4.86-7.11L4 12.5l.48-.88l1.79-3.24l.48-.88V3zM10 20.5v-6.25");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
