<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wzac4d8qi"/><path class="m8itrbbny"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:nft-collection" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m8itrbbny {
  d: path("M17.765 16.386za1.13 1.13 0 0 0 .951.691a.286.286 0 0 1 .163.503a1.13 1.13 0 0 0-.363 1.118a.286.286 0 0 1-.428.311a1.13 1.13 0 0 0-1.176 0a.286.286 0 0 1-.428-.311a1.13 1.13 0 0 0-.363-1.118a.286.286 0 0 1 .163-.503a1.13 1.13 0 0 0 .951-.691a.286.286 0 0 1 .53 0");
}

.wzac4d8qi {
  d: path("M6 2.5h1A3.5 3.5 0 0 1 10.5 6v1A3.5 3.5 0 0 1 7 10.5H6A3.5 3.5 0 0 1 2.5 7V6A3.5 3.5 0 0 1 6 2.5m11 0h1A3.5 3.5 0 0 1 21.5 6v1a3.5 3.5 0 0 1-3.5 3.5h-1A3.5 3.5 0 0 1 13.5 7V6A3.5 3.5 0 0 1 17 2.5m-11 11h1a3.5 3.5 0 0 1 3.5 3.5v1A3.5 3.5 0 0 1 7 21.5H6A3.5 3.5 0 0 1 2.5 18v-1A3.5 3.5 0 0 1 6 13.5m11 0h1a3.5 3.5 0 0 1 3.5 3.5v1a3.5 3.5 0 0 1-3.5 3.5h-1a3.5 3.5 0 0 1-3.5-3.5v-1a3.5 3.5 0 0 1 3.5-3.5");
}

</style>
