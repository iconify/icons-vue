<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s9utz-bmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:meet-the-team" /></template>
<style>
.s9utz-bmz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 8a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Zm-3 12.5c0-3.5 3-6 6.5-6c.942 0 1.848.181 2.669.514M16 4.5a3.5 3.5 0 0 1 .906 6.881M14.5 15h7v6.5h-7Zm0 2.5h7");
}

</style>
