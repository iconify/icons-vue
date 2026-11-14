<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="foda-7bhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:policy-document" /></template>
<style>
.foda-7bhn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 12.5v-10h14v7.1m0 10.3v1.6h-7.8M7 6h8M7 9.25h8M2.24 15.774l18.585-3.95l.935 4.402l-18.585 3.95Zm3.423-.727l.416 1.956m2.519-2.58l.312 1.467m2.622-2.091l.416 1.956m2.519-2.58l.312 1.468m2.622-2.091l.416 1.956");
}

</style>
