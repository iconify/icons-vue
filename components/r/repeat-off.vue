<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v630pskyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:repeat-off" /></template>
<style>
.v630pskyv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 13v-2.5q0-.431.122-.845q.121-.414.354-.777M11.408 7.5H19m-3-3l3 3l-3 3m3.5.5v2.5q0 .431-.121.845q-.122.414-.355.777M12.592 16.5H5m3-3l-3 3l3 3m-4.5-16l17 17");
}

</style>
