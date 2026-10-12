<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bkbvxeb5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:zen-stones-sharp" /></template>
<style>
.bkbvxeb5v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.25 18c0-3 1.6-5.25 3.75-5.25S15.75 15 15.75 18Zm1-9.25v-1.5h5.5v3h-5.5zM2.75 18h18.5m-15.5 0a6.5 6.5 0 0 1 .5-2.5m-3 2.5a9 9 0 0 1 .7-3.5m13.8 1a6.5 6.5 0 0 1 .5 2.5m1.8-3.5a9 9 0 0 1 .7 3.5m-18 2.75l2.33-.902l2.3.902l2.302.903L12 20.75l2.31-.9l2.31.9l2.308.899l2.322-.899");
}

</style>
