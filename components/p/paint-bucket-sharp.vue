<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g8auykb9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:paint-bucket-sharp" /></template>
<style>
.g8auykb9n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 9h11.5v12.25H3.75zm1.5 0C5.25 5.5 7 3.25 9.5 3.25S13.75 5.5 13.75 9m-10 3.5h11.5m4.5-.5l1.5 1.875V14.9a1.5 1.5 0 0 1-3 0v-1.025z");
}

</style>
