<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="orfhiupxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sunset-sharp" /></template>
<style>
.orfhiupxk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 17.5a5 5 0 0 1 10 0Zm-4.25 3.25h18.5M2.75 17.5H4.5m15 0h1.75M6 11.5l1.25 1.25M18 11.5l-1.25 1.25M12 2.75v6M9.5 6.5L12 9l2.5-2.5");
}

</style>
