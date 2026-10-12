<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="no-pljfhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:quarantine-file-sharp" /></template>
<style>
.no-pljfhk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 6.75h8v10.5H8zm2.5 3.5h3m-3 3h3M2.75 6.75v-4h4m10.5 0h4v4m0 10.5v4h-4m-10.5 0h-4v-4m7.75-14.5h3m-3 18.5h3M2.75 10.5v3m18.5-3v3");
}

</style>
