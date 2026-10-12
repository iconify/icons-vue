<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="kpf7rhbtb"/><path class="amquurkgr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:outlet-eco-sharp" /></template>
<style>
.amquurkgr {
  d: path("M8.75 18c.25-3.32 1.95-4.75 6.5-4.75C15 16.57 13.3 18 8.75 18Z");
}

.kpf7rhbtb {
  d: path("M4.5 2.75h15v18.5h-15zm5 3.5v3m5-3v3");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
