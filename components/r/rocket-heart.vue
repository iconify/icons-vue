<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s8zei2syp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:rocket-heart" /></template>
<style>
.s8zei2syp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5c3 2 3.5 5.5 3.5 8.5v2.5h-7V11c0-3 .5-6.5 3.5-8.5Zm-3.5 7l-2.25 2.25v1.75H8.5m7-4l2.25 2.25v1.75H15.5M12 18a1.75 1.75 0 0 0-3.5 0c0 1.5 2 2.5 3.5 3.75c1.5-1.25 3.5-2.25 3.5-3.75a1.75 1.75 0 0 0-3.5 0Z");
}

</style>
