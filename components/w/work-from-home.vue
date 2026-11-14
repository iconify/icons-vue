<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="k5mfw8-4w"/><path class="nnvzb1aji"/><path class="skb5wgeiw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:work-from-home" /></template>
<style>
.k5mfw8-4w {
  d: path("M3.5 11.5L12 4l8.5 7.5");
}

.nnvzb1aji {
  d: path("M5.5 10v10.5h13V10");
}

.skb5wgeiw {
  d: path("M8.5 13h7v4h-7Zm-1 7.5h9");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
