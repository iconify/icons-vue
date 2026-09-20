<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bgd5gjbdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:number-circle-1-16-filled" /></template>
<style>
.bgd5gjbdf {
  fill: currentColor;
  d: path("M8 1a7 7 0 1 0 0 14A7 7 0 0 0 8 1m1 4.25v5.25a.5.5 0 0 1-1 0V6.986a3.6 3.6 0 0 1-1.043.72a.5.5 0 1 1-.414-.911a2.7 2.7 0 0 0 1.174-1.046a3 3 0 0 0 .3-.628v-.005A.5.5 0 0 1 9 5.25");
}

</style>
