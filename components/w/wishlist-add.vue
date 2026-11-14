<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dj7un9b9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:wishlist-add" /></template>
<style>
.dj7un9b9s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 20.5s-8.5-5-8.5-11a4.5 4.5 0 0 1 8.5-2a4.5 4.5 0 0 1 8.5 2c0 1 0 1.5-.25 2.75h-6a2 2 0 0 0-2 2v5.25Zm6-5.5v6m-3-3h6");
}

</style>
