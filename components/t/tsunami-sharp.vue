<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rj7lv_47u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tsunami-sharp" /></template>
<style>
.rj7lv_47u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 16C6.5 16 7.5 12.75 8.5 9.5s3.5-6.25 7.25-6.25c3 0 5.5 2.25 5.5 5C20 7 16.75 6.75 16 10c-.75 3 .5 4.75 3 6Zm0 4.25q2.31-2 4.63 0t4.63 0t4.63 0t4.63 0");
}

</style>
