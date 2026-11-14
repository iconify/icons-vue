<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gmgd_yb4t"/><path class="pza4n9h4s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:street-light-double" /></template>
<style>
.gmgd_yb4t {
  d: path("M9 20.5h6m-3 0v-17m-7 3v-1a2 2 0 0 1 2-2h10a2 2 0 0 1 2 2v1");
}

.pza4n9h4s {
  fill: currentColor;
  d: path("M2 9.5a3 3 0 0 1 6 0Zm14 0a3 3 0 0 1 6 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
