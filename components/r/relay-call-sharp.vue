<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="yxdxo1bpb"/><path class="mgsv9hb9u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:relay-call-sharp" /></template>
<style>
.mgsv9hb9u {
  d: path("M14.25 2.75h7v6.5H17L14.75 11V9.25h-2.5v-6.5zM15 6h3.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yxdxo1bpb {
  d: path("M5 3.75h2.5L9.25 8l-2 1.25a11 11 0 0 0 5.5 5.5l1.25-2l4.25 1.75V19h-2A15 15 0 0 1 3 5.75v-2z");
}

</style>
