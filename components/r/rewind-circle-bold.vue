<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="fjtqr9cxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:rewind-circle-bold" /></template>
<style>
.fjtqr9cxk {
  fill: currentColor;
  d: path("M128 20a108 108 0 1 0 108 108A108.12 108.12 0 0 0 128 20m0 192a84 84 0 1 1 84-84a84.09 84.09 0 0 1-84 84m52-116v64a12 12 0 0 1-19.5 9.37l-36.5-29.2V160a12 12 0 0 1-19.5 9.37l-40-32a12 12 0 0 1 0-18.74l40-32A12 12 0 0 1 124 96v19.83l36.5-29.2A12 12 0 0 1 180 96");
}

</style>
