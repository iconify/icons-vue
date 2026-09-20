<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="vlkkaoofi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:superset-of-bold" /></template>
<style>
.vlkkaoofi {
  fill: currentColor;
  d: path("M220 200a12 12 0 0 1-12 12H56a12 12 0 0 1 0-24h152a12 12 0 0 1 12 12m-68-52H56a12 12 0 0 0 0 24h96a68 68 0 0 0 0-136H56a12 12 0 0 0 0 24h96a44 44 0 0 1 0 88");
}

</style>
