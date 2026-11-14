<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xqehlac9k"/><path class="xmw-0yb8s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:waste-rock-dump" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xmw-0yb8s {
  fill: currentColor;
  d: path("m14 6.5l2.25-.75L17 8l-2.25.75Zm2.5 5.5l2.25-1l1 2.25l-2.25 1Zm1.25 8.5l.75-3l2.25-.5l.75 3.5Z");
}

.xqehlac9k {
  d: path("M3 20.5L8.75 4L15 20.5m-12.5 0h19");
}

</style>
