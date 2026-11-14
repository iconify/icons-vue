<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x3-z5ab4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:shoe-cabinet" /></template>
<style>
.x3-z5ab4o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 11.5h18V19H3ZM5.5 19v2.5m13-2.5v2.5M6.5 8.75V3.5h4l1 2h3a3.25 3.25 0 0 1 3.25 3.25ZM12 11.5V19");
}

</style>
