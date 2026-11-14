<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jt808qbcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:person-welcome" /></template>
<style>
.jt808qbcz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 4.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0ZM3 7.5l4 3h10l4-3m-9 3V15m-4 6l4-6l4 6");
}

</style>
