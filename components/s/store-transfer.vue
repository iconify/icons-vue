<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="inkinmxjs"/><path class="l2qrbbcgq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:store-transfer" /></template>
<style>
.inkinmxjs {
  d: path("M11.664 21.332L3 17V7l9-4.5L21 7v4.538");
}

.l2qrbbcgq {
  d: path("m3 7l9 4.5L21 7m-9 4.5v1.7M7.5 4.75l9 4.5m-2 6.75h7m-1.75-1.75L21.5 16l-1.75 1.75M21.5 20h-7m1.75-1.75L14.5 20l1.75 1.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
