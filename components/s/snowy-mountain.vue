<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="f-grcgbqq"/><path class="zkj703b-d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:snowy-mountain" /></template>
<style>
.f-grcgbqq {
  d: path("m3 20l9-15l9 15Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zkj703b-d {
  d: path("m8 12.5l2 1.5l2-2l2 2l2-1.5m-10-6h.01M18 6.5h.01");
}

</style>
