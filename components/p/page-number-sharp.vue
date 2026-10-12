<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="x_i166bdm"/><path class="cf886ob_v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:page-number-sharp" /></template>
<style>
.cf886ob_v {
  d: path("m11 15.5l1.5-1.25v4.5");
}

.x_i166bdm {
  d: path("M3.75 2.75h16.5v18.5H3.75zM7.5 7h9m-9 3.5h9");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
