<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w0yjumbbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pet-ear-cleaner" /></template>
<style>
.w0yjumbbi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.5 3.75c-3-1.25-6-.25-7 3.25l-4 1.75c-1.25.5-1.25 2.5 0 3l4.25 1C8.5 15.5 10 17 12 17.5m5.235-5.507c-1.492-.761-2.486-3.509-2.735-8.243c3.5-.5 5.75 2.75 5.75 5.75c0 .987-.289 1.734-.74 2.198M10.5 7.5h.01m7.99 7.25c-1.5 1.75-3 3-3 4.25a3 3 0 0 0 6 0c0-1.25-1.5-2.5-3-4.25Z");
}

</style>
