<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="el1u_q36i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:matrix-logo-bold" /></template>
<style>
.el1u_q36i {
  fill: currentColor;
  d: path("M76 216a12 12 0 0 1-12 12H40a12 12 0 0 1-12-12V40a12 12 0 0 1 12-12h24a12 12 0 0 1 0 24H52v152h12a12 12 0 0 1 12 12M216 28h-24a12 12 0 0 0 0 24h12v152h-12a12 12 0 0 0 0 24h24a12 12 0 0 0 12-12V40a12 12 0 0 0-12-12m-28 132v-40a36 36 0 0 0-60-26.8a35.91 35.91 0 0 0-39.51-5.68A12 12 0 0 0 68 96v64a12 12 0 0 0 24 0v-40a12 12 0 0 1 24 0v40a12 12 0 0 0 24 0v-40a12 12 0 0 1 24 0v40a12 12 0 0 0 24 0");
}

</style>
