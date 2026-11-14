<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rc64qxb9w"/><path class="c1yol3w-u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:playback-speed" /></template>
<style>
.c1yol3w-u {
  d: path("M10.25 15.5L14.5 18l-4.25 2.5Z");
}

.rc64qxb9w {
  d: path("M4.25 17a9 9 0 1 1 15.5 0M12 12.5l4.25-4.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
