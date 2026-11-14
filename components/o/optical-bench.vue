<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="erwmf_b7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:optical-bench" /></template>
<style>
.erwmf_b7c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 16h19m-18 0v3.5m17-3.5v3.5M3.75 9a1.75 4.5 0 1 0 3.5 0a1.75 4.5 0 1 0-3.5 0Zm6.5 0a1.75 4.5 0 1 0 3.5 0a1.75 4.5 0 1 0-3.5 0Zm6.5 0a1.75 4.5 0 1 0 3.5 0a1.75 4.5 0 1 0-3.5 0ZM5.5 13.5V16m6.5-2.5V16m6.5-2.5V16");
}

</style>
