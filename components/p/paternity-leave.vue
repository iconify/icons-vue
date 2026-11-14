<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mo01j74go"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:paternity-leave" /></template>
<style>
.mo01j74go {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M19.499 9.609c-.072 3.18-3.305 4.891-8.249 4.891c-5 0-8.25-1.75-8.25-5h11.9m2.4 0h1.9M3 9.5c0-4 3-7 7-7v7m-6.25 9.75a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m10.5 0a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m2.375-15.5l.839.516a1.5 1.5 0 0 0 1.572 0l.839-.516a1.066 1.066 0 0 1 1.625.908v1.184a1.066 1.066 0 0 1-1.625.908l-.839-.516a1.5 1.5 0 0 0-1.572 0l-.839.516A1.066 1.066 0 0 1 15 5.842V4.658a1.066 1.066 0 0 1 1.625-.908");
}

</style>
