<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f_v4gubge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tagging-gun" /></template>
<style>
.f_v4gubge {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 4.5H18v6H3.5Zm6 6H14L13 21H8.5Zm8.5-3h3.5m-15 3V13c0 1.5.75 2.5 2 2.5M7 4.5v-2m3.5 2v-2");
}

</style>
