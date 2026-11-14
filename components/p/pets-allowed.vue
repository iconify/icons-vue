<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ovdt6crgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pets-allowed" /></template>
<style>
.ovdt6crgx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 11.5c3.5 0 6.5 4 6.5 6.75c0 2-1.75 3-3.5 2.5c-1.25-.35-2-.75-3-.75s-1.75.4-3 .75c-1.75.5-3.5-.5-3.5-2.5c0-2.75 3-6.75 6.5-6.75ZM7.25 5.25a1.5 2.25 0 1 0 3 0a1.5 2.25 0 1 0-3 0Zm6.5 0a1.5 2.25 0 1 0 3 0a1.5 2.25 0 1 0-3 0Zm-11 5a1.5 2 0 1 0 3 0a1.5 2 0 1 0-3 0Zm15.5 0a1.5 2 0 1 0 3 0a1.5 2 0 1 0-3 0Z");
}

</style>
