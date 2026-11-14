<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="sth84_b8f"/><path class="qmfmmibza"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pos-layaway" /></template>
<style>
.qmfmmibza {
  d: path("m3 7l9 4.5L21 7m-9 4.5v.9M7.5 4.75l9 4.5m-2 6h7v6.5h-7Zm0 2.5h7m-5-3.75v1.75m3-1.75v1.75");
}

.sth84_b8f {
  d: path("M11.664 21.332L3 17V7l9-4.5L21 7v4.238");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
