<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z88gruand"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:newt" /></template>
<style>
.z88gruand {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5c1.6 0 2.75 1.1 2.75 2.5c0 .9-.45 1.6-1 2C14.6 7.6 15 8.5 15 9.5v4c0 1.5-.6 2.5-1.5 3c-.75 2-2 4-4.5 5c1.25-1.75 1.5-3.5 1.5-5C9.6 16 9 15 9 13.5v-4c0-1 .4-1.9 1.25-2.5c-.55-.4-1-1.1-1-2c0-1.4 1.15-2.5 2.75-2.5Zm3 7l3-.75l.5-2.25M9 9.5l-3-.75l-.5-2.25m9.5 7l3 1l.5 2.5M9 13.5l-3 1l-.5 2.5M12 9.5V14");
}

</style>
