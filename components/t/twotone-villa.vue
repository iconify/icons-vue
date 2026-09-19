<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c4g9bnbwd"/><path class="ghk06fbfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-villa" /></template>
<style>
.c4g9bnbwd {
  fill: currentColor;
  d: path("m5 9.37l9-3.46V12H9v7H5zM19 19h-3v-3h-2v3h-3v-5h8z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.ghk06fbfp {
  fill: currentColor;
  d: path("M19 10c-1.1 0-2 .9-2 2h-1V3L3 8v13h18v-9c0-1.1-.9-2-2-2M5 9.37l9-3.46V12H9v7H5zM19 19h-3v-3h-2v3h-3v-5h8z");
}

</style>
