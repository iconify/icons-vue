<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mfx146rff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:medical-gloves" /></template>
<style>
.mfx146rff {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m8.5 16.5l-3-3.5c-.75-.75-.5-1.75.25-2.25c.75-.25 1.5-.25 2 .75l1 1.25v-7.5c0-.75.75-1.5 1.5-1.5s1.25.75 1.25 1.5v5v-6.5c0-.5.75-1.25 1.5-1.25c.5 0 1.25.75 1.25 1.25v6.5v-5c0-.75.75-1.5 1.25-1.5c.75 0 1.5.75 1.5 1.5v5.25v-3c0-.75.5-1.5 1.25-1.5s1.5.75 1.5 1.5v6.25c0 1.75-1 2.75-2 3.25M6.5 21.5L8 17.25h10.25l1.5 4.25Z");
}

</style>
