<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dh0uj2bqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:repeat-off-sharp" /></template>
<style>
.dh0uj2bqz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 11.25v-5h15.5M16.5 3l3.25 3.25L16.5 9.5m3.25 3.25v5H4.25M7.5 21l-3.25-3.25L7.5 14.5");
}

</style>
