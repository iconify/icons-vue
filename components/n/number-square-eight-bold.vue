<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="yqnmr2b3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:number-square-eight-bold" /></template>
<style>
.yqnmr2b3g {
  fill: currentColor;
  d: path("M208 28H48a20 20 0 0 0-20 20v160a20 20 0 0 0 20 20h160a20 20 0 0 0 20-20V48a20 20 0 0 0-20-20m-4 176H52V52h152ZM88 152a40 40 0 1 0 67.6-28.91a36 36 0 1 0-55.2 0A39.87 39.87 0 0 0 88 152m40 16a16 16 0 1 1 16-16a16 16 0 0 1-16 16m-12-68a12 12 0 1 1 12 12a12 12 0 0 1-12-12");
}

</style>
