<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ctxb9ubwr"/><path class="scden-bnu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:soccer-field-top" /></template>
<style>
.ctxb9ubwr {
  d: path("M2.5 5h19v14h-19ZM12 5v14");
}

.scden-bnu {
  d: path("M9 12a3 3 0 1 0 6 0a3 3 0 1 0-6 0ZM2.5 9h3v6h-3m19-6h-3v6h3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
