<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q8jxr_b4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:makeup-brush-sharp" /></template>
<style>
.q8jxr_b4i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4 20l6.36-6.36m-.71-1.41l2.13-2.13l.35-.35l.35.35l1.42 1.42l.35.35l-.35.35l-2.13 2.13l-.35.35l-.35-.35l-1.42-1.42l-.35-.35zm2.83-3.68l.19-.61l.35-1.2l1.06-.66l.7-.45l1.06-.66l1.2.34l.08.03l1.2.34l.34 1.2l.03.08l.34 1.2l-.66 1.06l-.45.7l-.66 1.06l-1.2.35l-.61.19l-1.2.35l-.88-.88l-.36-.36l-.88-.88z");
}

</style>
