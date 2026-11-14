<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z_v-3u8rv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:thought-bubble" /></template>
<style>
.z_v-3u8rv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 13.5h10a3.5 3.5 0 1 0-.5-7a4.5 4.5 0 1 0-9 0a3.5 3.5 0 1 0-.5 7Zm-.25 4a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm-3.25 3a1 1 0 1 0 2 0a1 1 0 1 0-2 0Z");
}

</style>
