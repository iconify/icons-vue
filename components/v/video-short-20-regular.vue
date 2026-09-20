<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="d4stoebcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:video-short-20-regular" /></template>
<style>
.d4stoebcw {
  fill: currentColor;
  d: path("M13.154 2.004A3 3 0 0 1 16 5v10a3 3 0 0 1-3 3H7a3 3 0 0 1-3-3V5a3 3 0 0 1 3-3h6zM7 3a2 2 0 0 0-2 2v10a2 2 0 0 0 2 2h6a2 2 0 0 0 2-2V5a2 2 0 0 0-1.796-1.99L13 3zm1 5.502a1 1 0 0 1 1.514-.858l2.504 1.498a1 1 0 0 1 0 1.716l-2.504 1.498A1 1 0 0 1 8 11.498z");
}

</style>
