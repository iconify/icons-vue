<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qvfifrb1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:martial-arts-sharp" /></template>
<style>
.qvfifrb1w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 7.5H9.5v4.25H2.75zm11.75 0h6.75v4.25H14.5zm-5-1.75h5v7.5h-5zm0 9h1.25l-.25.71l-1.75 4.83l-.25.71l-.73-.16l-.79-.18l-.73-.16l.3-.69l1.9-4.37l.3-.69zm4.5 0h1.25l.3.69l1.9 4.37l.3.69l-.73.16l-.79.18l-.73.16l-.25-.71l-1.75-4.83l-.25-.71z");
}

</style>
