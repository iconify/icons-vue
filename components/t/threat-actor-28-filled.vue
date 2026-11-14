<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="v9s3x9bsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:threat-actor-28-filled" /></template>
<style>
.v9s3x9bsa {
  fill: currentColor;
  d: path("M26 18.024a5.976 5.976 0 0 1-10.26 4.165l-.665-.683a1.5 1.5 0 0 0-2.15 0l-.665.683A5.976 5.976 0 0 1 2 18.025V14.5h24zM5.402 16.5a3 3 0 0 0 5.197 3zm12 3a3 3 0 0 0 5.197-3zM14.002 2c4.842 0 9.011 2.87 10.907 7h.591a1.5 1.5 0 0 1 1.5 1.5v1a1.5 1.5 0 0 1-1.5 1.5h-23A1.5 1.5 0 0 1 1 11.5v-1A1.5 1.5 0 0 1 2.5 9h.595C4.99 4.87 9.16 2 14.002 2");
}

</style>
