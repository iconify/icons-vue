<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q_dm9eb2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:uv-index" /></template>
<style>
.q_dm9eb2s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 8.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0ZM8 4.25V2.5m-4.25 6H2m3-3L3.75 4.25M11 5.5l1.25-1.25M5 11.5l-1.25 1.25m8.5-4.25H14M9.5 14v4.5a2.5 2.5 0 0 0 5 0V14m2.75 0l2 7l2-7");
}

</style>
