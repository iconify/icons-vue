<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="emlkgbbur"/><path class="kvv17u8-b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pipe-wrench-sharp" /></template>
<style>
.emlkgbbur {
  d: path("m16.42 2.81l3.18 3.18l-5.66 5.66m2.13-2.12L13.24 6.7m-1.42 7.07l-1.41 1.41m0 0h0l1.06 1.06l-1.06 1.06l-2.83 2.83l-1.06 1.06l-1.06-1.06l-1.06-1.06l1.06-1.06l2.83-2.83l1.06-1.06z");
}

.kvv17u8-b {
  d: path("m13.06 10.76l1.77 1.77l.53.53l-.53.53l-1.06 1.06l-.53.53l-.53-.53l-1.77-1.77l-.53-.53l.53-.53L12 10.76l.53-.53z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
