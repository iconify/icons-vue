<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o4dik7a6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:maternity-leave" /></template>
<style>
.o4dik7a6g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 4.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM8.5 21v-6c-1-4 .5-6.5 3-6.5c3 0 6 2 5 6l-1 1.5v5");
}

</style>
