<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tc-xy_p4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:summer-calendar" /></template>
<style>
.tc-xy_p4f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.9 20H3V4.5h16v7.4M7.5 2.5v4m7-4v4M3 9.5h16M16.5 18a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm1.5-3.25v.75m0 5v.75M14.75 18h.75m5 0h.75");
}

</style>
