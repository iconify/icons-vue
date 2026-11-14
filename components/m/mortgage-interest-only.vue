<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nzecq3b5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mortgage-interest-only" /></template>
<style>
.nzecq3b5h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4 10.5l2-1.75M7.5 7.5L9.25 6m1.5-1.5l1.25-1l.75.5m1.5 1.5L16 7m1.5 1.25l2 1.75m.5 1.75v2.5m0 2v2.5m-.25 1.75h-2.5m-2 0h-2.5m-2 0h-2.5m-2 0H4v-.25m0-2v-2.5m0-2v-2.5M9 18l6-6.5m-7.25.75a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Zm6 5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Z");
}

</style>
