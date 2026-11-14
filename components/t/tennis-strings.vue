<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pr51aubmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tennis-strings" /></template>
<style>
.pr51aubmg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 9a6.5 7 0 1 0 13 0a6.5 7 0 1 0-13 0Zm6.5 7v5.5m-2.25-19v13m4.5-13v13m-8.5-8.75h12.5m-12.5 4.5h12.5");
}

</style>
