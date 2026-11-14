<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="erir83cbs"/><path class="r1ejtm6oq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:org-tree" /></template>
<style>
.erir83cbs {
  d: path("M3.5 5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm11 5.25a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm0 7.75a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Z");
}

.r1ejtm6oq {
  d: path("M6 7.5V16a2 2 0 0 0 2 2h6.5M6 10.25h8.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
