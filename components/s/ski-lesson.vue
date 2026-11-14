<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zwv9mac2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ski-lesson" /></template>
<style>
.zwv9mac2j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 8.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM2.5 17.5C2.5 14.5 4 13 6 13s3.5 1.5 3.5 4.5m-7 3H10m2.5-18h9v7h-9Zm1 18l1-11m5 0l1 11M8 13.5L12.5 7");
}

</style>
