<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xbblkkrbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:shape-union" /></template>
<style>
.xbblkkrbq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 2.75h8.5a2 2 0 0 1 2 2v4h4a2 2 0 0 1 2 2v8.5a2 2 0 0 1-2 2h-8.5a2 2 0 0 1-2-2v-4h-4a2 2 0 0 1-2-2v-8.5a2 2 0 0 1 2-2");
}

</style>
