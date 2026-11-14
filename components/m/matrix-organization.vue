<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="do0mb1bum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:matrix-organization" /></template>
<style>
.do0mb1bum {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 15a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0ZM8.5 21.5c0-1.75 1.5-2.75 3.5-2.75s3.5 1 3.5 2.75M2.75 4.75a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm-.5 6.75C2.25 9.75 3.5 8.75 5 8.75s2.75 1 2.75 2.75Zm14.5-6.75a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm-.5 6.75c0-1.75 1.25-2.75 2.75-2.75s2.75 1 2.75 2.75Zm-10 .25L10 14m7.75-2.25L14 14");
}

</style>
