<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p31zdw96a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:probation-period" /></template>
<style>
.p31zdw96a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 2.5h14m-14 19h14M6.5 2.5C6.5 8 11 9.5 11 12s-4.5 4-4.5 9.5m11-19c0 5.5-4.5 7-4.5 9.5s4.5 4 4.5 9.5m-5.5 0v-4m0 1c0-1.5 1-2.5 2.25-2.5c0 1.5-1 2.5-2.25 2.5Zm0 1C12 18 11 17 9.75 17c0 1.5 1 2.5 2.25 2.5Z");
}

</style>
