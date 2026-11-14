<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hwqawdb6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:symptom-checker" /></template>
<style>
.hwqawdb6g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.023 19.256c-.19.157-.46.244-.773.244h-1c-.5 0-1-.5-1-1L10 15a.781.781 0 0 0-1.5 0l-.25 3.5c0 .5-.5 1-1 1h-1c-.75 0-1.25-.5-1-1.25L6 14l.5-2l-1.25 1.5c-.25.5-.5.75-1.25.75c-1 0-1.5-.5-1.25-1.5l2-2.5C5 9 6 8.75 7.25 8.75h4c1.25 0 2.25.25 2.5 1.5l1.656 2.07m-1.812 1.671c-.138-.121-.241-.285-.344-.491L12 12l.5 2l.484 2.743M7.25 4.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm8.5 12.25c0-1.25 1-2 2.25-2s2.25.75 2.25 2C20.25 18 18 18 18 19.25m0 2.25h.01");
}

</style>
