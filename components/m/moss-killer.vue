<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r9gebbb_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:moss-killer" /></template>
<style>
.r9gebbb_s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 21.5v-9a2 2 0 0 1 2-2h4a2 2 0 0 1 2 2v9Zm2.5-11v-6h7V7H9.5v3.5m4.5 1c1-2.5 3-2.5 3.75-1.25C18.5 9 20.5 9 21.5 11.5m-6 4l5 5m0-5l-5 5");
}

</style>
