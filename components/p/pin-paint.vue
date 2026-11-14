<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bk9d44r3k"/><path class="v7nwq4d0a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pin-paint" /></template>
<style>
.bk9d44r3k {
  d: path("M3.5 2.5H18v6H3.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v7nwq4d0a {
  d: path("M18 5.5h2.5v6H12V14m-1.5 0h3v7.5h-3Z");
}

</style>
