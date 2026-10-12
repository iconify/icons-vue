<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h6skllb7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:necklace-sharp" /></template>
<style>
.h6skllb7p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 2.75c.5 7 3.5 11 7.75 11.75c4.25-.75 7.25-4.75 7.75-11.75m-7.22 12.78l1.94 1.94l.53.53l-.51.55l-1.98 2.15l-.51.55l-.51-.55l-1.98-2.15L9 18l.53-.53l1.94-1.94L12 15z");
}

</style>
