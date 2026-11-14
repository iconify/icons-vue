<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="la0ufkb2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:scene-reading" /></template>
<style>
.la0ufkb2u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 12c-1.75-1.25-4.75-1.5-8.5-1v8.5c3.75-.5 6.75-.25 8.5 1c1.75-1.25 4.75-1.5 8.5-1V11c-3.75-.5-6.75-.25-8.5 1Zm0 0v8.5m6-17.25l1.061 1.689L20.75 6l-1.689 1.061L18 8.75l-1.061-1.689L15.25 6l1.689-1.061Z");
}

</style>
