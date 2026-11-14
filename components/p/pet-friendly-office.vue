<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ii5nrnj0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pet-friendly-office" /></template>
<style>
.ii5nrnj0l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 12.5c-3 0-5.5 3-5.5 5.25c0 1.75 1.5 2.75 3 2.25c1-.3 1.75-.5 2.5-.5s1.5.2 2.5.5c1.5.5 3-.5 3-2.25c0-2.25-2.5-5.25-5.5-5.25Zm-9.5-2a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm4.25-4.75a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm6.5 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm4.25 4.75a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

</style>
