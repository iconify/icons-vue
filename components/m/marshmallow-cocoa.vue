<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="sgjbtc6qp"/><path class="salm5bqme"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:marshmallow-cocoa" /></template>
<style>
.salm5bqme {
  d: path("M6.25 5.25H10V9H6.25Zm4.5-.75h3.75v3.75h-3.75Z");
}

.sgjbtc6qp {
  d: path("M4.5 8h11v9a3.5 3.5 0 0 1-3.5 3.5H8A3.5 3.5 0 0 1 4.5 17Zm11 2H17a2.5 2.5 0 0 1 0 5h-1.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
