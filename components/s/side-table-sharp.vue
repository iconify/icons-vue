<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lu8bxcckv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:side-table-sharp" /></template>
<style>
.lu8bxcckv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.25 5.75h5.5v4.5h-5.5zm1.25 0v-2.5h3v2.5m-9.75 4.5h16.5v3H3.75zm8.25 3v8m-3.75 0h7.5");
}

</style>
