<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n1pyhi5nv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tooth-candy" /></template>
<style>
.n1pyhi5nv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 7.75a4 3.5 0 1 0 8 0a4 3.5 0 1 0-8 0M6.245 6.521l-.885-.619A1.5 1.5 0 0 0 3 7.131v1.238a1.5 1.5 0 0 0 2.36 1.229l.885-.619a1.5 1.5 0 0 0 0-2.458m11.51 0l.885-.619A1.5 1.5 0 0 1 21 7.131v1.238a1.5 1.5 0 0 1-2.36 1.229l-.885-.619a1.5 1.5 0 0 1 0-2.458M16.5 15c-1.25 0-1.75 1-1.75 2.25s.75 1.75 1 2.75l.5 1.5l1.5-2l1.5 2l.5-1.5c.25-1 1-1.5 1-2.75S20.25 15 19 15c-.75 0-.75.5-1.25.5s-.5-.5-1.25-.5");
}

</style>
