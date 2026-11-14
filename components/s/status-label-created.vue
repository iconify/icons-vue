<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ljoshbbnu"/><path class="s6krrlqxp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:status-label-created" /></template>
<style>
.ljoshbbnu {
  d: path("M2.5 12L8 6h13v12H8Zm5 0h.01");
}

.s6krrlqxp {
  d: path("m11.5 12l2.5 2.5l4-5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
