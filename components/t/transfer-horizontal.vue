<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xjij0h9dq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:transfer-horizontal" /></template>
<style>
.xjij0h9dq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 7a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm6 0h11m-3.5-3.5L20 7l-3.5 3.5M17 17a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-2 0H4m3.5-3.5L4 17l3.5 3.5");
}

</style>
