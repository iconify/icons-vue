<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="opf6ubcjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:polytunnel-sharp" /></template>
<style>
.opf6ubcjk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 21.25v-6a8.5 8.5 0 0 1 8.5-8.5h1.5a8.5 8.5 0 0 1 8.5 8.5v6ZM7.5 8.5v12.75M12 6.75v14.5M16.5 8.5v12.75M12 6.75c0-2 1.25-3.25 3.25-4c0 2-1.25 3.25-3.25 4Z");
}

</style>
