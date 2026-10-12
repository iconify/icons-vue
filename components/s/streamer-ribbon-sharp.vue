<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gv_ygrj_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:streamer-ribbon-sharp" /></template>
<style>
.gv_ygrj_v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 3.25h18.5M6 3.25C4.25 5.5 7.75 6.5 6 8.75s1.75 3.25 0 5.5s1.75 3.25 0 5.5m6-16.5c-1.75 2.25 1.75 3.25 0 5.5s1.75 3.25 0 5.5s1.75 3.25 0 5.5m6-16.5c-1.75 2.25 1.75 3.25 0 5.5s1.75 3.25 0 5.5");
}

</style>
