<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b_xz0zbfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:studio-apartment" /></template>
<style>
.b_xz0zbfp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 5.5v15M3 17h8.4M3 12.5h12.2m-9.7-3h5v3h-5Zm8.75 6.75h7.5m-6.75 0v3.5a1.75 1.75 0 0 0 1.75 1.75h2.5A1.75 1.75 0 0 0 21 19.75v-3.5m-3-2V15");
}

</style>
