<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="qotlaf_8a"/><path class="fcwap2bjm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:security-token-sharp" /></template>
<style>
.fcwap2bjm {
  d: path("M12 5.75a1.5 1.5 0 1 1 0 3a1.5 1.5 0 1 1 0-3m-2.75 6h5.5v6h-5.5zm1.5 3h.75m1 0h.75");
}

.qotlaf_8a {
  d: path("M6.25 2.75h11.5v18.5H6.25z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
