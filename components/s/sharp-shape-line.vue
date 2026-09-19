<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w-cnjq42m"/><path class="ktuctggsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-shape-line" /></template>
<style>
.ktuctggsk {
  fill: currentColor;
  d: path("M17.71 7.7c.4.19.83.3 1.29.3c1.65 0 3-1.35 3-3s-1.35-3-3-3s-3 1.35-3 3c0 .46.11.89.3 1.29L6.29 16.3c-.4-.19-.83-.3-1.29-.3c-1.65 0-3 1.35-3 3s1.35 3 3 3s3-1.35 3-3c0-.46-.11-.89-.3-1.29z");
}

.w-cnjq42m {
  fill: currentColor;
  d: path("M6 11c2.76 0 5-2.24 5-5S8.76 1 6 1S1 3.24 1 6s2.24 5 5 5m17 3h-9v9h9z");
}

</style>
