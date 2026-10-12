<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="dzdbch7tn"/><path class="iudiszbon"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:scale-bar-sharp" /></template>
<style>
.dzdbch7tn {
  d: path("M2.75 9.75h18.5v4.5H2.75z");
}

.iudiszbon {
  d: path("M8.92 9.75h6.17v4.5H8.92zM3.5 17.5V20m8.5-2.5V20m8.5-2.5V20");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
