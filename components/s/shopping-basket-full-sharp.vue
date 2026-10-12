<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="yij3ylb0l"/><path class="o3s0krbzt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:shopping-basket-full-sharp" /></template>
<style>
.o3s0krbzt {
  d: path("M13.25 2.75h3.5V10h-3.5zM4.25 13h15.5l1.276.001l-.306 1.239l-1.25 5.1l-.464 1.91H4.994l-.464-1.91l-1.25-5.1l-.306-1.239zM9 15.25v3m3-3v3m3-3v3");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yij3ylb0l {
  cx: 8px;
  cy: 7.25px;
  r: 2.75px;
}

</style>
