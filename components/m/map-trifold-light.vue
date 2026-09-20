<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="m71ri3-_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:map-trifold-light" /></template>
<style>
.m71ri3-_r {
  fill: currentColor;
  d: path("M227.69 51.27a6 6 0 0 0-5.15-1.09L160.7 65.64l-62-31a6 6 0 0 0-4.14-.45l-64 16A6 6 0 0 0 26 56v144a6 6 0 0 0 7.46 5.82l61.84-15.46l62 31a6 6 0 0 0 4.14.45l64-16A6 6 0 0 0 230 200V56a6 6 0 0 0-2.31-4.73M102 49.71l52 26v130.58l-52-26Zm-64 11l52-13v131.61l-52 13Zm180 134.61l-52 13V76.68l52-13Z");
}

</style>
