<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="lzm24bcjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:tent-bold" /></template>
<style>
.lzm24bcjq {
  fill: currentColor;
  d: path("m255 187.13l-64-144A12 12 0 0 0 180 36H76a12 12 0 0 0-10.85 6.9a2 2 0 0 0-.12.23l-.03.17L1 187.13A12 12 0 0 0 12 204h232a12 12 0 0 0 11-16.87M64 104.55V180H30.46ZM88 180v-75.45L121.54 180Zm59.8 0L94.47 60h77.73l53.34 120Z");
}

</style>
