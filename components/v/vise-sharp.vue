<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y3jqs6n-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:vise-sharp" /></template>
<style>
.y3jqs6n-a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 18.75h16v2.5H4zM4 8h6v10.75H4zm1.75 3.5h2.5M14 8h4v7.5h-4zm4 3.75h3m0-2.5v5");
}

</style>
