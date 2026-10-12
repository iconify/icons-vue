<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="bx7jubbpy"/><circle class="zgau9oblh"/><path class="ojqgu4b9u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:notification-square-sharp" /></template>
<style>
.bx7jubbpy {
  d: path("M11.75 6.25h-9v15h15v-9a6.25 6.25 0 0 1-6-6Z");
}

.ojqgu4b9u {
  d: path("M6.5 13H12m-5.5 3.75H10");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zgau9oblh {
  cx: 18px;
  cy: 6px;
  r: 3.25px;
}

</style>
