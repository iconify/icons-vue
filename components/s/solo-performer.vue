<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jdbd9mbux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:solo-performer" /></template>
<style>
.jdbd9mbux {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 11a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0ZM7.75 21.5c0-3.5 1.75-5.25 4.25-5.25s4.25 1.75 4.25 5.25M9 2.5l-6 19m12-19l6 19");
}

</style>
