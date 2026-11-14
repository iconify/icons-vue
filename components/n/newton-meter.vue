<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wzgj8tbps"/><path class="au1r4ab_q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:newton-meter" /></template>
<style>
.au1r4ab_q {
  d: path("M9 6h6v11H9Zm3 11v2.5a2 2 0 0 1-4 0m1-10h2.5m-2.5 4h2.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wzgj8tbps {
  d: path("M10 4a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

</style>
