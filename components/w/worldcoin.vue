<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mxj1cbcri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:worldcoin" /></template>
<style>
.mxj1cbcri {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M2.5 24.015C2.5 12.133 12.126 2.5 24 2.5c7.91 0 14.821 4.274 18.555 10.64m0 0A21.4 21.4 0 0 1 45.5 24.015m0 0H13.68c0-4.575 2.58-10.875 12.652-10.875h16.223M13.68 23.985H2.5C2.5 35.867 12.126 45.5 24 45.5c7.91 0 14.821-4.274 18.555-10.64m0 0A21.4 21.4 0 0 0 45.5 23.985m-31.82 0c0 4.575 2.58 10.875 12.652 10.875h16.223");
}

</style>
