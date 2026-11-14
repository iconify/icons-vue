<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kgztb-c7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:wifi-password" /></template>
<style>
.kgztb-c7d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 18.5h.01m-2.485-2.475a3.5 3.5 0 0 1 4.95 0M4.55 13.55a7 7 0 0 1 9.9 0M2.751 10.457a10.5 10.5 0 0 1 13.498 0M14.75 17.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm3.5 0h3.25v1.75");
}

</style>
