<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gmjnzgtgx"/><path class="d9h5sgbzf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:snowboard-halfpipe" /></template>
<style>
.d9h5sgbzf {
  d: path("m10.341 5.531l8.156-3.804l1.162 2.492l-8.156 3.804Z");
}

.gmjnzgtgx {
  d: path("M4 8v4a8 8 0 0 0 16 0V8");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
