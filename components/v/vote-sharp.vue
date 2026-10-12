<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="eveaq_b5o"/><path class="osbxmfqcc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:vote-sharp" /></template>
<style>
.eveaq_b5o {
  d: path("M8.25 2.75h7.5v8h-7.5z");
}

.osbxmfqcc {
  d: path("M10.25 6.75L11.5 8l2.25-2.5m-10 7.75h16.5v8H3.75zm4.5 3.5h7.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
