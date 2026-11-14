<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m9wgk1ogn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:security-guard-hotel" /></template>
<style>
.m9wgk1ogn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6.5 7.5l-2-3.25c4.75-2.5 10.25-2.5 15 0l-2 3.25Zm1.5 0V10a4 4 0 0 0 8 0V7.5m-11.5 14C4.5 19 7.75 17 12 17s7.5 2 7.5 4.5M12 5h.01");
}

</style>
