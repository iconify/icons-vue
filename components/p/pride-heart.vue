<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j4fpjhb2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pride-heart" /></template>
<style>
.j4fpjhb2b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 20S3 14.5 3 8.75C3 6.1 5.1 4 7.75 4C9.5 4 11.1 5 12 6.5C12.9 5 14.5 4 16.25 4C18.9 4 21 6.1 21 8.75C21 14.5 12 20 12 20ZM6 9.25h12m-10 4h8");
}

</style>
