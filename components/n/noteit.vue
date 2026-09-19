<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="cnuosl17d"/><path class="i899t7bye"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:noteit" /></template>
<style>
.cnuosl17d {
  d: path("M38.5 5.5h-29c-2.2 0-4 1.8-4 4v29c0 2.2 1.8 4 4 4h22.835V32.335H42.5V9.5c0-2.2-1.8-4-4-4m4 26.835L32.335 42.5M5.5 11.809h37");
}

.i899t7bye {
  d: path("m24 19.258l-1.256-1.256a4.25 4.25 0 0 0-5.988 0h0a4.25 4.25 0 0 0 0 5.988l1.256 1.256m11.976 0l1.256-1.256a4.25 4.25 0 0 0 0-5.988h0a4.25 4.25 0 0 0-5.988 0L24 19.258m-5.988 5.988L24 31.235l5.988-5.989");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
