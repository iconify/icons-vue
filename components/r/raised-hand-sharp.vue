<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dylbxugbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:raised-hand-sharp" /></template>
<style>
.dylbxugbl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 14.5V6.75h2.5V8V3.5h2.5v1.25V3h2.5v2.25V4h2.5v8.5l1.6-1.6a1.4 1.4 0 0 1 2 2l-3.6 4.35a5.5 5.5 0 0 1-3.75 4h-.75a5.5 5.5 0 0 1-5.5-5.5Zm2.5-6V12m2.5-7v7m2.5-6.5V12");
}

</style>
