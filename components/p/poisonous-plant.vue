<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tehd-io6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:poisonous-plant" /></template>
<style>
.tehd-io6q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 21.5V10m0 4c-3.5 0-6-2.5-6-6c3.5 0 6 2.5 6 6Zm0-4c0-3.5 2.5-6.5 6.5-6.5c0 4-2.5 6.5-6.5 6.5Zm6.5 5.5l5 5m0-5l-5 5");
}

</style>
