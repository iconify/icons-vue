<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="t05uyv95l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:tree-evergreen-bold" /></template>
<style>
.t05uyv95l {
  fill: currentColor;
  d: path("M233.47 184.63L192.54 132H208a12 12 0 0 0 9.51-19.32l-80-104a12 12 0 0 0-19 0l-80 104A12 12 0 0 0 48 132h15.46l-40.93 52.63A12 12 0 0 0 32 204h84v36a12 12 0 0 0 24 0v-36h84a12 12 0 0 0 9.47-19.37M56.54 180l40.93-52.63A12 12 0 0 0 88 108H72.37L128 35.68L183.63 108H168a12 12 0 0 0-9.47 19.37L199.46 180Z");
}

</style>
