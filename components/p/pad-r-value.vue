<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="acwk11b_s"/><path class="i44rpmzss"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pad-r-value" /></template>
<style>
.acwk11b_s {
  d: path("M14.725 13.5H3l4.5-9H21l-1.985 3.969M6 7.5h13.5m-15 3h10.25M17.5 17v-4.75a1 1 0 0 1 2 0V17");
}

.i44rpmzss {
  d: path("M16.75 18.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
